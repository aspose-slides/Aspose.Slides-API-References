---
title: IFontFallBackRule
second_title: Aspose.Slides for Java API Reference
description: Представляет правило резервного шрифта
type: docs
url: /ru/com.aspose.slides/ifontfallbackrule/
---```
public interface IFontFallBackRule
```

Представляет правило резервного шрифта
## Методы

| Method | Description |
| --- | --- |
| [addFallBackFonts(String fontName)](#addFallBackFonts-java.lang.String-) | Добавляет новый шрифт(ы) в список FallBack шрифтов. |
| [addFallBackFonts(String[] fontNames)](#addFallBackFonts-java.lang.String---) | Добавляет новые шрифты в список FallBack шрифтов. |
| [getRangeStartIndex()](#getRangeStartIndex--) | Получает первый индекс непрерывного диапазона Unicode. |
| [getRangeEndIndex()](#getRangeEndIndex--) | Получает последний индекс непрерывного диапазона Unicode. |
| [getCount()](#getCount--) | Получает количество шрифтов, фактически определённых для диапазона. |
| [get_Item(int index)](#get-Item-int-) | Получает имя шрифта по указанному индексу. |
| [clear()](#clear--) | Удаляет все шрифты из списка. |
| [remove(String fontName)](#remove-java.lang.String-) | Удаляет первое вхождение конкретного FallBack шрифта из списка. |
| [removeAt(int index)](#removeAt-int-) | Удаляет FallBack шрифт по указанному индексу в списке. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми FallBack шрифтами для этого правила. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со всеми FallBack шрифтами из указанного диапазона в списке. |
| [indexOf(String fontName)](#indexOf-java.lang.String-) | Возвращает индекс указанного правила в коллекции. |
### addFallBackFonts(String fontName) {#addFallBackFonts-java.lang.String-}
```
public abstract void addFallBackFonts(String fontName)
```

Добавляет новый шрифт(ы) в список FallBack шрифтов.

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
| fontName | java.lang.String | Имя(а) шрифта (разделённые запятыми) для FallBack |

### addFallBackFonts(String[] fontNames) {#addFallBackFonts-java.lang.String---}
```
public abstract void addFallBackFonts(String[] fontNames)
```

Добавляет новые шрифты в список FallBack шрифтов.

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
| fontNames | java.lang.String[] | Имя(а) шрифта (разделённые запятыми) для FallBack |

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

Получает количество шрифтов, фактически определённых для диапазона.

**Возвращаемое значение:**
int
### get_Item(int index) {#get-Item-int-}
```
public abstract String get_Item(int index)
```

Получает имя шрифта по указанному индексу.

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

Удаляет первое вхождение конкретного FallBack шрифта из списка.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Удаление Tahoma из списка
>  newRule.remove("Tahoma");
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта, которое нужно удалить из списка. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет FallBack шрифт по указанному индексу в списке.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Удаление Tahoma из списка
>  newRule.remove(2);
```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс шрифта, который требуется удалить. |

### toArray() {#toArray--}
```
public abstract String[] toArray()
```

Создаёт и возвращает массив со всеми FallBack шрифтами для этого правила.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Получить все имена шрифтов как массив
>  String[] fontNames = newRule.toArray();
```

**Возвращаемое значение:**
java.lang.String[] - массив строк
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract String[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив со всеми FallBack шрифтами из указанного диапазона в списке.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Получить последние два имени шрифта как массив
>  String[] fontNames = newRule.toArray(2,2);
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
public abstract int indexOf(String fontName)
```

Возвращает индекс указанного правила в коллекции.

--------------------

> ```
> // Создать правило, содержащее список шрифтов.
>  IFontFallBackRule newRule = new FontFallBackRule(0x3040, 0x309F, "MS Mincho, MS Gothic, Tahoma, Times New Roman");
>  // Получить индекс Tahoma
>  int tahomaIndex = newRule.indexOf("Tahoma");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fontName | java.lang.String | Имя шрифта для поиска. |

**Возвращаемое значение:**
int - индекс шрифта или -1, если шрифт не найден в списке.