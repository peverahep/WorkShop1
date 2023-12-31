# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]

Отчет по лабораторной работе #1 выполнил(а):

- Мальцев Богдан Андреевич
- ФО-220005

  Отметка о выполнении заданий (заполняется студентом):

| Задание   | Выполнение | Баллы |
| --------- | ---------- | ----- |
| Задание 1 | \*         | 60    |
| Задание 2 | \*         | 20    |
| Задание 3 | \*         | 20    |

знак "\*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:

- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы

установить необходимое программное обеспечение, которое пригодится для создания интеллектуальных моделей на Python. Рассмотреть процесс установки игрового движка Unity для разработки игр.

Ход работы:

## Задание 1

### Написать программу Hello World на Python с запуском в Jupiter Notebook.

-С помощью "Anaconda Navigator" запустить JupiterNotebook

-Средствами JupiterNotebook создать новый файл с разрешением .ipynb

-Использоать встроенную функцию вывода "рrint()" для вывода сообщения "Hello world!!!" на консоль.

```py
print("Hello World!!!")
```

## Задание 2

### Написать программу Hello World на C# с запуском на Unity.

-С помощью графического интерфейса Unity создадим новый C# скрипт.

-Преобразем метод Update следующим образом:

```cs
using System.Collections;
using System.Collections.Generic;
using UnityEngine;

public class Hello_World : MonoBehaviour
{
    bool isMessagePrinted = false;
    void Start()
    {

    }

    // Update is called once per frame
    void Update()
    {
        if (!isMessagePrinted)
        {
            Debug.Log("Hello World!!!");
            isMessagePrinted=true;
        }
    }
}
```

## Задание 3

### Оформить отчет в виде документации на github (markdown-разметка)

-С помощью средств Visual Studio Code и его встроенного расширения "Preview MarkDown File" был создан данных отчёт.

-С помощью утилиты GitHub Desktop данный отчёт был выгружен на GitHub.

## Выводы

В ходе проделанной работы были изучены такие инструменты, как: Anakonda Navigator, JupiterNotebook, Unity 3D, Python, C#
В ходе лабораторной:

1. Я научился работать с Anakonda Navigator
2. Я смог вывести на консоль "Hello World!!!" с помощью программы на пайтон и JupiterNotebook
3. Я создал скрипт, который заставляет любой объект в Unity, с учётом прикрепления к нему скрипт-файла, писать в консоль "Hello World!!!", при этом только 1 раз
4. Я изучил GitHub Desktop, смог создать репозиторий, создать отчёт и выгрузить отчёт в соответствующий репозиторий на платформе "GitHub".

Цели лабораторной работы были достигнуты.

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
