---
title: IFontFallBackRule
second_title: Aspose.Slides for Android via Java API Reference
description: Represents font fallback rule
type: docs
url: /ru/com.aspose.slides/ifontfallbackrule/
---``` 
public interface IFontFallBackRule 
```

Представляет правило подстановки шрифта
## Методы

| Метод | Описание |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Добавляет новый шрифт(и) в список резервных шрифтов. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Добавляет новые шрифты в список резервных шрифтов. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Получает первый индекс непрерывного диапазона Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Получает последний индекс непрерывного диапазона Unicode. |
| [getCount()](#getCount--) | Возвращает количество шрифтов, фактически определённых для диапазона. |
| [get_Item(int index)](#get-Item-int-) | Возвращает имя шрифта по указанному индексу. |
| [clear()](#clear--) | Удаляет все шрифты из списка. |
| [remove(String fontName)](#remove-java.lang.String-) | Удаляет первое вхождение указанного резервного шрифта из списка. |
| [removeAt(int index)](#removeAt-int-) | Удаляет резервный шрифт по указанному индексу в списке. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми резервными шрифтами для этого правила. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со всеми резервными шрифтами из заданного диапазона списка. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Возвращает индекс указанного правила в коллекции. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
``` 
public abstract void addFallBackFonts(String fontName) 
```

Добавляет новый шрифт(и) в список резервных шрифтов.

--------------------

> ``` 
> //Создание нового экземпляра FantFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Добавить второй шрифт к правилу 
>  newRule.addFallBackFonts("MS Gothic");
>  //Добавить третий и четвертый шрифты к правилу 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта или имена (разделённые запятыми) для резервного шрифта |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
``` 
public abstract void addFallBackFonts(String[] fontNames)
```

Добавляет новые шрифты в список резервных шрифтов.

--------------------

> ```
> //Создание нового экземпляра FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Добавление ещё трёх шрифтов к правилу 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontNames | java.lang.String[] | Имя шрифта или имена (разделённые запятыми) для резервного шрифта |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public abstract long getRangeStartIndex()
```

Получает первый индекс непрерывного диапазона Unicode.

**Возвращаемое значение:**
long
### getRangeEndIndex() {#getRangeEndIndex--}
```
public abstract long getRangeEndIndex()
```

Получает последний индекс непрерывного диапазона Unicode.

**Возвращаемое значение:**
long
### getCount() {#getCount--}
```
public abstract int getCount()
```

Возвращает количество шрифтов, фактически определённых для диапазона.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Возвращает имя шрифта по указанному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
java.lang.String
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все шрифты из списка.

### remove(String fontName) {#remove-java.lang.String-}
``` 
public abstract void remove(String fontName)
```

Удаляет первое вхождение указанного резервного шрифта из списка.

--------------------

> ```
> // Создание правила, содержащего список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Удаление Tahoma из списка
>  newRule.remove("Tahoma");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта, которое следует удалить из списка. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет резервный шрифт по указанному индексу в списке.

--------------------

> ```
> // Создание правила, содержащего список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Удаление Tahoma из списка
>  newRule.remove(2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс шрифта, который следует удалить. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Создаёт и возвращает массив со всеми резервными шрифтами для этого правила.

--------------------

> ```
> // Создание правила, содержащего список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Получить все имена шрифтов в виде массива
>  String[] fontNames = newRule.toArray();
> ```

**Возвращаемое значение:**
java.lang.String[] - Массив строк
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив со всеми резервными шрифтами из заданного диапазона списка.

--------------------

> ```
> // Создание правила, содержащего список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
> //Получить последние два имени шрифта в виде массива
>  String[] fontNames = newRule.toArray(2,2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого шрифта для добавления. |
| count | int | Количество шрифтов для добавления. |

**Возвращаемое значение:**
java.lang.String[] - Массив строк
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String fontName)
```

Возвращает индекс указанного правила в коллекции.

--------------------

> ```
> // Создание правила, содержащего список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Получить индекс Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта для поиска. |

**Возвращаемое значение:**
int - Индекс шрифта или -1, если шрифт не найден в списке.