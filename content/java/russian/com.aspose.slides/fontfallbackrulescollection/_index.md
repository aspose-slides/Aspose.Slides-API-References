---
title: FontFallBackRulesCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию правил FontFallBack, определённых пользователем
type: docs
url: /ru/com.aspose.slides/fontfallbackrulescollection/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

Представляет коллекцию правил FontFallBack, определённых пользователем
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Возвращает количество правил, фактически содержащихся в коллекции. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | Добавляет указанное правило FallBack в конец коллекции. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | Удаляет первое вхождение конкретного правила FallBack из коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает правило по указанному индексу. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает корень синхронизации. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


Возвращает количество правил, фактически содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```


Добавляет указанное правило FallBack в конец коллекции.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Getting of empty or preinitialized rules collection from FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Adding of new rule to collection
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Указанное правило для добавления |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```


Удаляет первое вхождение конкретного правила FallBack из коллекции.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Получение пустой или предварительно инициализированной коллекции правил из FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Добавление нескольких правил в коллекцию
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Получение объекта первого правила в коллекции
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //Удаление
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | Правило, которое нужно удалить из коллекции. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


Возвращает правило по указанному индексу. Только для чтения [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //Получение пустой или предварительно инициализированной коллекции правил из FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //Добавление нескольких правил в коллекцию
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //Получение объекта первого правила в коллекции
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


Возвращает перечислитель, который проходит по коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Копирует все элементы из коллекции в указанный массив.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Целевой массив. |
| index | int | Начальный индекс в целевом массиве. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Только для чтения boolean.

**Возвращает:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Возвращает корень синхронизации. Только для чтения Object.

**Возвращает:**
java.lang.Object