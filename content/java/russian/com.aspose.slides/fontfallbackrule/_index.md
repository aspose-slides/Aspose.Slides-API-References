---
title: FontFallBackRule
second_title: Справочник API Aspose.Slides для Java
description: Представляет правило резервного шрифта
type: docs
url: /ru/com.aspose.slides/fontfallbackrule/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
```
public class FontFallBackRule implements IFontFallBackRule
```

Представляет правило резервного шрифта
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontFallBackRule(long startIndex, long endIndex, String fontNames)](#FontFallBackRule-long-long-java.lang.String-) | Создает новый экземпляр. |
| [FontFallBackRule(long startIndex, long endIndex, String[] fontNames)](#FontFallBackRule-long-long-java.lang.String---) | Создает новый экземпляр. |
## Методы

| Метод | Описание |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Добавляет новый шрифт(ы) в список резервных шрифтов. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Добавляет новые шрифты в список резервных шрифтов. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Получает первый индекс непрерывного диапазона Unicode. |
| [setRangeStartIndex(long value)](#setRangeStartIndex-long-) | Получает первый индекс непрерывного диапазона Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Получает последний индекс непрерывного диапазона Unicode. |
| [setRangeEndIndex(long value)](#setRangeEndIndex-long-) | Получает последний индекс непрерывного диапазона Unicode. |
| [getCount()](#getCount--) | Получает количество шрифтов, реально определенных для диапазона. |
| [get_Item(int index)](#get-Item-int-) | Получает имя шрифта по указанному индексу. |
| [clear()](#clear--) | Удаляет все шрифты из списка. |
| [remove(String fontName)](#remove-java.lang.String-) | Удаляет первое вхождение конкретного резервного шрифта из списка. |
| [removeAt(int index)](#removeAt-int-) | Удаляет резервный шрифт по указанному индексу в списке. |
| [toArray()](#toArray--) | Создает и возвращает массив со всеми резервными шрифтами для данного правила. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создает и возвращает массив со всеми резервными шрифтами из указанного диапазона в списке. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Возвращает индекс указанного правила в коллекции. |
### FontFallBackRule(long startIndex, long endIndex, String fontNames) {#FontFallBackRule-long-long-java.lang.String-}
```
public FontFallBackRule(long startIndex, long endIndex, String fontNames)
```

Создает новый экземпляр.

--------------------

> ```
> // Создать новый экземпляр FantFallBackRule с одним шрифтом.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  // Создать новый экземпляр FantFallBackRule с несколькими шрифтами.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | long | Начальный индекс диапазона Unicode |
| endIndex | long | Конечный индекс диапазона Unicode |
| fontNames | java.lang.String | Имя или имена шрифта (разделенные запятыми) для резервного шрифта |

### FontFallBackRule(long startIndex, long endIndex, String[] fontNames) {#FontFallBackRule-long-long-java.lang.String---}
```
public FontFallBackRule(long startIndex, long endIndex, String[] fontNames)
```

Создает новый экземпляр.

--------------------

> ```
> // Создать новый экземпляр FantFallBackRule с двумя шрифтами
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Mincho", "MS Gothic"});
>  // Создать новый экземпляр FantFallBackRule с несколькими шрифтами.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, new String[] { "MS Gothic", "Tahoma, Times New Roman" });
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | long | Начальный индекс диапазона Unicode |
| endIndex | long | Конечный индекс диапазона Unicode |
| fontNames | java.lang.String[] | Имя или имена шрифта (разделенные запятыми) для резервного шрифта |

### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public final void addFallBackFonts(String fontName)
```

Добавляет новый шрифт(ы) в список резервных шрифтов.

--------------------

> ```
> // Создать новый экземпляр FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Добавить второй шрифт к правилу 
>  newRule.addFallBackFonts("MS Gothic");
>  //Добавить третий и четвертый шрифты к правилу 
>  newRule.addFallBackFonts("Tahoma, Times New Roman");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя или имена шрифта (разделенные запятыми) для резервного шрифта |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public final void addFallBackFonts(String[] fontNames)
```

Добавляет новые шрифты в список резервных шрифтов.

--------------------

> ```
> //Создать новый экземпляр FontFallBackRule
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho");
>  //Добавить еще три шрифта к правилу 
>  newRule.addFallBackFonts(new String [] {"MS Gothic","Tahoma, Times New Roman"});
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontNames | java.lang.String[] | Имя или имена шрифта (разделенные запятыми) для резервного шрифта |

### getRangeStartIndex() {#getRangeStartIndex--}
```
public final long getRangeStartIndex()
```

Получает первый индекс непрерывного диапазона Unicode.

**Возвращаемое значение:**
long
### setRangeStartIndex(long value) {#setRangeStartIndex-long-}
```
public final void setRangeStartIndex(long value)
```

Получает первый индекс непрерывного диапазона Unicode.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getRangeEndIndex() {#getRangeEndIndex--}
```
public final long getRangeEndIndex()
```

Получает последний индекс непрерывного диапазона Unicode.

**Возвращаемое значение:**
long
### setRangeEndIndex(long value) {#setRangeEndIndex-long-}
```
public final void setRangeEndIndex(long value)
```

Получает последний индекс непрерывного диапазона Unicode.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |

### getCount() {#getCount--}
```
public final int getCount()
```

Получает количество шрифтов, реально определенных для диапазона. Только для чтения int.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public final String get_Item(int index)
```

Получает имя шрифта по указанному индексу. Только для чтения [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
java.lang.String
### clear() {#clear--}
```
public final void clear()
```

Удаляет все шрифты из списка.

### remove(String fontName) {#remove-java.lang.String-}
```
public final void remove(String fontName)
```

Удаляет первое вхождение конкретного резервного шрифта из списка.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Удалить Tahoma из списка.
>  newRule.remove("Tahoma");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта, которое нужно удалить из списка. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет резервный шрифт по указанному индексу в списке.

--------------------

> ```
> //Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  //Удаление Tahoma из списка.
>  newRule.remove(2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой базовый индекс шрифта, который необходимо удалить. |

### toArray() {#toArray--}
```
public final String[] toArray()
```

Создает и возвращает массив со всеми резервными шрифтами для данного правила.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Получить все имена шрифтов в виде массива.
>  String[] fontNames = newRule.toArray();
> ```

**Возвращаемое значение:**
java.lang.String[] - массив строк
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final String[] toArray(int startIndex, int count)
```

Создает и возвращает массив со всеми резервными шрифтами из указанного диапазона в списке.

```
// Создать правило, содержащее список шрифтов.
 IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
 // Получить последние два имени шрифта в виде массива.
 String[] fontNames = newRule.toArray(2, 2);
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого шрифта для добавления. |
| count | int | Количество шрифтов для добавления. |

**Возвращаемое значение:**
java.lang.String[] - массив строк
### indexOf(String fontName) {#indexOf-java.lang.String-}
```
public final int indexOf(String fontName)
```

Возвращает индекс указанного правила в коллекции.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Получить индекс Tahoma.
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта для поиска. |

**Возвращаемое значение:**
int - индекс шрифта или -1, если шрифт не найден в списке.