# TL :: Описание и техническая информация по проекту

## Содержание

* [1 Введение](#1-Введение)
* [2 Миссия](#2-Миссия)
* [3 Функциональные возможности и особенности](#3-Функциональные-возможности-и-особенности)
* [4 Этапы развития проекта](#4-Этапы-развития-проекта)
* [5 Монетизация](#5-Монетизация)
* [6 Физическая архитектура](#6-Физическая-архитектура)
  * [6.1 Сервисы](#61-Сервисы)
    * [6.1.1 Клиентская часть](#611-Клиентская-часть)
      * [6.1.1.1 Web-версия (`tl-webui`)](#6111-Web-версия-(`tl-webui`))
      * [6.1.1.2 Мобильное приложение iOS/Android (`tl-app`)](#6112-Мобильное-приложение-iOS/Android-(`tl-app`))
    * [6.1.2 Серверная часть](#612-Серверная-часть)
      * [6.1.2.1 Узел публичного шлюза - **TL API** (`tl-api`)](#6121-Узел-публичного-шлюза---**TL-API**-(`tl-api`))
      * [6.1.2.2 Узел производительного сервера - **TL SERVER** (`tl-srv`)](#6122-Узел-производительного-сервера---**TL-SERVER**-(`tl-srv`))
      * [6.1.2.3 Узел репликации/трансляции данных - **TL DB WRAPPER** (`tl-dbw`)](#6123-Узел-репликации/трансляции-данных---**TL-DB-WRAPPER**-(`tl-dbw`))
      * [6.1.2.4 Очередь задач узлам производительных серверов - **RabbitMQ for TL SERVER** (`tl-qsrv`)](#6124-Очередь-задач-узлам-производительных-серверов---**RabbitMQ-for-TL-SERVER**-(`tl-qsrv`))
      * [6.1.2.5 Очередь задач узелам репликации/трансляции данных - **RabbitMQ for TL DB WRAPPER** (`tl-qdbw`)](#6125-Очередь-задач-узелам-репликации/трансляции-данных---**RabbitMQ-for-TL-DB-WRAPPER**-(`tl-qdbw`))
  * [6.2 Взаимодействие](#62-Взаимодействие)
* [7 Логическая архитектура](#7-Логическая-архитектура)

***

## 1 Введение

**TL** (аббривеатура от **T**echno**L**ogic - *бывш. Технологика*) - это совокупная система микросервиосов, работающих вместе с целью формирования высоконагруженной отказоустойчивой распределенной системы интерактивного тестирования для проведения интеллектуально-развлекательных личных и командных состязаний.
***

## 2 Миссия

...
***

## 3 Функциональные возможности и особенности

...
***

## 4 Этапы развития проекта

...
***

## 5 Монетизация

...
***

## 6 Физическая архитектура

...

### 6.1 Сервисы

...

#### 6.1.1 Клиентская часть

...

##### 6.1.1.1 Web-версия (`tl-webui`)

>Angular CLI

...

##### 6.1.1.2 Мобильное приложение iOS/Android (`tl-app`)

>Xamarin

...

#### 6.1.2 Серверная часть

...

##### 6.1.2.1 Узел публичного шлюза - **TL API** (`tl-api`)

>.NET Core

...

##### 6.1.2.2 Узел производительного сервера - **TL SERVER** (`tl-srv`)

>C++

...

##### 6.1.2.3 Узел репликации/трансляции данных - **TL DB WRAPPER** (`tl-dbw`)

>C++

...

##### 6.1.2.4 Очередь задач узлам производительных серверов - **RabbitMQ for TL SERVER** (`tl-qsrv`)

>RabbitMQ

...

##### 6.1.2.5 Очередь задач узелам репликации/трансляции данных - **RabbitMQ for TL DB WRAPPER** (`tl-qdbw`)

>RabbitMQ

...

### 6.2 Взаимодействие

...
***

## 7 Логическая архитектура

...
***
