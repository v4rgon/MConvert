# Требования к проекту
---
# Содержание
1. [Введение](#intro)  
 	1.1 [Назначение](#appointment)  
  	1.2   [Бизнес-требования](#business_requirements)  
  	1.2.1 [Исходные данные](#initial_data)  
  	1.2.2 [Возможности бизнеса](#business_opportunities)  
  	1.2.3 [Границы проекта](#project_boundary)  
  	1.3   [Аналоги](#analogues)  

  2. [Требования пользователя](#user_requirements)  
  	2.1 [Программные интерфейсы](#software_interfaces)  
  	2.2 [Интерфейс пользователя](#user_interface)  
  	2.3 [Характеристики пользователей](#user_specifications)  
  	2.3.1 [Классы пользователей](#user_classes)  
  	2.3.2 [Аудитория приложения](#application_audience)  

  3. [Системные требования](#system_requirements)  
  	3.1 [Функциональные требования](#functional_requirements)  
  	3.1.1 [Основные функции](#main_functions)    
  	3.1.2 [Ограничения и исключения](#restrictions_and_exclusions)  
  	3.2 [Нефункциональные требования](#non-functional_requirements)  
  	3.2.1 [Атрибуты качества](#quality_attributes)  
  	3.2.1.1 [Требования к удобству использования](#requirements_for_ease_of_use)   
  	3.2.2 [Ограничения](#restrictions)  

<a name="intro"/>

# 1 Введение

<a name="appointment"/>

## 1.1 Назначение
MConvert - это мобильное приложение, предназначенное для отображения настоящего курса валют, конвертирования их, а также поиска банков в вашем регионе с самым выгодным курсом.

<a name="business_requirements"/>

## 1.2 Бизнес-требования

<a name="initial_data"/>

### 1.2.1 Исходные данные
Конвертер валют является удобным инструментом, с помощью которого можно быстро найти выгодные курсы валют.

<a name="business_opportunities"/>

### 1.2.2 Возможности бизнеса
Данное приложение подойдет как для тех, кто просто хочет воспользоваться калькулятором, так и для тех, кто хочет поменять валюту и ищет самый выгодный курс.

<a name="project_boundary"/>

### 1.2.3 Границы проекта
Приложение позволит найти выгодный курс и воспользоваться калькулятором.

<a name="analogues"/>

## 1.3 Аналоги

["Конвертера валют онлайн"](https://myfin.by/converter/)

["Финансы TUT.BY"](https://finance.tut.by/).

<a name="user_requirements"/>

# 2 Требования пользователя

<a name="software_interfaces"/>

## 2.1 Программные интерфейсы
Для написания приложения будет использоваться интегрированная среда разработки Android Studio и библиотека JSOUP для парсинга сайтов с курсами валют.

<a name="user_interface"/>

## 2.2 Интерфейс пользователя
# Главное окно приложения.
![Окно курса валют](../Mockups/Currency.png)

# Окно конвертации валют.
![Окно конвертации валют ](../Mockups/Converter.png)

# Окно поиска банков с лучшими курсами.
![Окно поиска банков](../Mockups/BestBanks.png)

<a name="user_specifications"/>

## 2.3 Характеристики пользователей

<a name="user_classes"/>

### 2.3.1 Классы пользователей

Пользователи, которые вошли в приложение имеют доступ к полному функционалу.

<a name="application_audience"/>

### 2.3.2 Аудитория приложения

<a name="target_audience"/>

#### 2.3.2.1 Целевая аудитория
Люди всех возрастных категорий.


<a name="system_requirements"/>

# 3 Системные требования

<a name="functional_requirements"/>
 1. Необходим доступ к интернету для обновления всей финансовой информации и работы с настоящими курсами. Приложением также можно пользоваться и "оффлайн", но вся информация будет устаревшей.

## 3.1 Функциональные требования

<a name="main_functions"/>

### 3.1.1 Основные функции

Пользователю предоставлены возможности, предоставленные в таблице.

Функция | Требования
--- | ---
Конвертация валют | Приложение должно конвертировать валюту разных стран при нажатии на соответствующую кнопку
Отображение валют | Приложение должно отображать курсы наиболее востребованных валют на главном экране
Поиск выгодных курсов | Приложение должно предоставлять информацию о банках, у которых наиболее выгодные курсы на текущий день, при выборе двух желаемых валют

<a name="restrictions_and_exclusions"/>

### 3.1.2 Ограничения и исключения
1. Запуск и работа приложения на следующих операционных системах:
* Android 5.1 и выше

<a name="non-functional_requirements"/>

## 3.2 Нефункциональные требования

<a name="quality_attributes"/>

### 3.2.1 Атрибуты качества

<a name="requirements_for_ease_of_use"/>

#### 3.2.1.1 Требования к удобству использования
1. Доступ к основным функциям приложения не более чем за три операции;
2. Все функциональные элементы пользовательского интерфейса имеют названия, описывающие действие, которое произойдет при выборе элемента;


<a name="restrictions"/>

### 3.2.2 Ограничения
1. Приложение реализовано под платформу Android версии 5.1.1 и выше;
