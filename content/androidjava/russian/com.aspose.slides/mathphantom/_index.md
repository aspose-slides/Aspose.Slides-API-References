---
title: MathPhantom
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет призрачный математический объект ltmphantgt, который влияет на расположение дочернего элемента, не обязательно отображая его.
type: docs
url: /ru/com.aspose.slides/mathphantom/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

Представляет «призрачный» математический объект (<m:phant>), который влияет на расположение дочернего элемента, не обязательно отображая его. Призрак может скрывать базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования пространства. Видимость и поведение геометрии контролируются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // Скрыть содержимое
>  phantom.setZeroWidth(false);     // Сохранить ширину
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Инициализирует новый экземпляр класса [MathPhantom](../../com.aspose.slides/mathphantom) с использованием указанного базового математического элемента. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getShow()](#getShow--) | Получает или задает значение, указывающее, отображается ли базовый элемент. |
| [setShow(boolean value)](#setShow-boolean-) | Получает или задает значение, указывающее, отображается ли базовый элемент. |
| [getZeroWidth()](#getZeroWidth--) | Получает или задает значение, указывающее, должна ли ширина базового элемента считаться нулевой. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Получает или задает значение, указывающее, должна ли ширина базового элемента считаться нулевой. |
| [getZeroAsc()](#getZeroAsc--) | Получает или задает значение, указывающее, должна ли высота подъёма (высота над базовой линией) базового элемента считаться нулевой. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Получает или задает значение, указывающее, должна ли высота подъёма (высота над базовой линией) базового элемента считаться нулевой. |
| [getZeroDesc()](#getZeroDesc--) | Получает или задает значение, указывающее, должна ли глубина спуска (глубина ниже базовой линии) базового элемента считаться нулевой. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Получает или задает значение, указывающее, должна ли глубина спуска (глубина ниже базовой линии) базового элемента считаться нулевой. |
| [getTransp()](#getTransp--) | Получает или задает значение, указывающее, является ли призрак прозрачным для правил расстановки пробелов, основанных на классах. |
| [setTransp(boolean value)](#setTransp-boolean-) | Получает или задает значение, указывающее, является ли призрак прозрачным для правил расстановки пробелов, основанных на классах. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

Инициализирует новый экземпляр класса [MathPhantom](../../com.aspose.slides/mathphantom) с использованием указанного базового математического элемента.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый [IMathElement](../../com.aspose.slides/imathelement), чья видимость и расположение будут контролироваться призраком. Этот элемент определяет содержимое, которое может быть скрыто или отображено, одновременно влияя на геометрическое выравнивание окружающей формулы.

--------------------

Элемент-призрак используется для резервирования или подавления визуального пространства базового выражения без обязательного отображения его. Он соответствует элементу OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Базовый аргумент

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

Получает или задает значение, указывающее, отображается ли базовый элемент.

--------------------

Если значение ложно, базовый элемент скрыт, но может по-прежнему занимать пространство в зависимости от других настроек призрака. Соответствует атрибуту OMML m:show.

**Возвращаемое значение:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Получает или задает значение, указывающее, отображается ли базовый элемент.

--------------------

Если значение ложно, базовый элемент скрыт, но может по-прежнему занимать пространство в зависимости от других настроек призрака. Соответствует атрибуту OMML m:show.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Получает или задает значение, указывающее, должна ли ширина базового элемента считаться нулевой.

--------------------

Если значение истинно, призрак не резервирует горизонтальное пространство для своей основы. Соответствует атрибуту OMML m:zeroWid.

**Возвращаемое значение:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Получает или задает значение, указывающее, должна ли ширина базового элемента считаться нулевой.

--------------------

Если значение истинно, призрак не резервирует горизонтальное пространство для своей основы. Соответствует атрибуту OMML m:zeroWid.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Получает или задает значение, указывающее, должна ли высота подъёма (высота над базовой линией) базового элемента считаться нулевой.

--------------------

Если значение истинно, призрак не повышает базовую линию окружающей математической строки. Соответствует атрибуту OMML m:zeroAsc.

**Возвращаемое значение:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Получает или задает значение, указывающее, должна ли высота подъёма (высота над базовой линией) базового элемента считаться нулевой.

--------------------

Если значение истинно, призрак не повышает базовую линию окружающей математической строки. Соответствует атрибуту OMML m:zeroAsc.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Получает или задает значение, указывающее, должна ли глубина спуска (глубина ниже базовой линии) базового элемента считаться нулевой.

--------------------

Если значение истинно, призрак не понижает базовую линию окружающей математической строки. Соответствует атрибуту OMML m:zeroDesc.

**Возвращаемое значение:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Получает или задает значение, указывающее, должна ли глубина спуска (глубина ниже базовой линии) базового элемента считаться нулевой.

--------------------

Если значение истинно, призрак не понижает базовую линию окружающей математической строки. Соответствует атрибуту OMML m:zeroDesc.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Получает или задает значение, указывающее, является ли призрак прозрачным для правил расстановки пробелов, основанных на классах.

--------------------

Если значение истинно, операторы и символы внутри призрака всё ещё влияют на математическое расположение пробелов (как если бы они были видимы). Если значение ложно, правила расстановки, основанные на классах, игнорируются. Соответствует атрибуту OMML m:transp.

**Возвращаемое значение:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Получает или задает значение, указывающее, является ли призрак прозрачным для правил расстановки пробелов, основанных на классах.

--------------------

Если значение истинно, операторы и символы внутри призрака всё ещё влияют на математическое расположение пробелов (как если бы они были видимы). Если значение ложно, правила расстановки, основанные на классах, игнорируются. Соответствует атрибуту OMML m:transp.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Свойства управляющих символов

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]