---
title: MathPhantom
second_title: Справка API Aspose.Slides для Java
description: Представляет невидимый математический объект ltmphantgt, который влияет на расположение дочернего элемента, не обязательно отображая его.
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

Представляет невидимый математический объект (<m:phant>), который влияет на расположение дочернего элемента, не обязательно отображая его. Невидимый объект может скрыть базовое выражение, сохраняя его ширину, высоту или глубину для выравнивания формул или резервирования пространства. Видимость и геометрическое поведение управляются свойствами, такими как Show, ZeroWid, ZeroAsc, ZeroDesc и Transp.

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
| [getZeroWidth()](#getZeroWidth--) | Получает или задает значение, указывающее, следует ли рассматривать ширину базового элемента как нулевую. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Получает или задает значение, указывающее, следует ли рассматривать ширину базового элемента как нулевую. |
| [getZeroAsc()](#getZeroAsc--) | Получает или задает значение, указывающее, следует ли рассматривать подъем (высоту над базовой линией) базового элемента как нулевой. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Получает или задает значение, указывающее, следует ли рассматривать подъем (высоту над базовой линией) базового элемента как нулевой. |
| [getZeroDesc()](#getZeroDesc--) | Получает или задает значение, указывающее, следует ли рассматривать спуск (глубину ниже базовой линии) базового элемента как нулевой. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Получает или задает значение, указывающее, следует ли рассматривать спуск (глубину ниже базовой линии) базового элемента как нулевой. |
| [getTransp()](#getTransp--) | Получает или задает значение, указывающее, является ли phantom прозрачным для правил интервалов, основанных на классах. |
| [setTransp(boolean value)](#setTransp-boolean-) | Получает или задает значение, указывающее, является ли phantom прозрачным для правил интервалов, основанных на классах. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый [IMathElement](../../com.aspose.slides/imathelement), чья видимость и расположение будут контролироваться phantom. Этот элемент определяет содержимое, которое может быть скрыто или отображено, при этом всё равно влияя на геометрическое выравнивание окружающей формулы. |

Элемент phantom используется для резервирования или подавления визуального пространства своего базового выражения без обязательного его отображения. Он соответствует элементу OMML <m:phant>. |

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

Если false, базовый элемент скрыт, но может всё равно занимать место в зависимости от других настроек phantom. Соответствует атрибуту OMML m:show.

**Возвращаемое значение:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

Получает или задает значение, указывающее, отображается ли базовый элемент.

--------------------

Если false, базовый элемент скрыт, но может всё равно занимать место в зависимости от других настроек phantom. Соответствует атрибуту OMML m:show.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

Получает или задает значение, указывающее, следует ли рассматривать ширину базового элемента как нулевую.

--------------------

Если true, phantom не резервирует горизонтальное пространство для своего базового элемента. Соответствует атрибуту OMML m:zeroWid.

**Возвращаемое значение:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

Получает или задает значение, указывающее, следует ли рассматривать ширину базового элемента как нулевую.

--------------------

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

Получает или задает значение, указывающее, следует ли рассматривать подъем (высоту над базовой линией) базового элемента как нулевой.

--------------------

Если true, phantom не повышает базовую линию окружающей математической строки. Соответствует атрибуту OMML m:zeroAsc.

**Возвращаемое значение:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

Получает или задает значение, указывающее, следует ли рассматривать подъем (высоту над базовой линией) базового элемента как нулевой.

--------------------

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

Получает или задает значение, указывающее, следует ли рассматривать спуск (глубину ниже базовой линии) базового элемента как нулевой.

--------------------

Если true, phantom не понижает базовую линию окружающей математической строки. Соответствует атрибуту OMML m:zeroDesc.

**Возвращаемое значение:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

Получает или задает значение, указывающее, следует ли рассматривать спуск (глубину ниже базовой линии) базового элемента как нулевой.

--------------------

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

Получает или задает значение, указывающее, является ли phantom прозрачным для правил интервалов, основанных на классах.

--------------------

Если true, операторы и символы внутри phantom все равно влияют на математические интервалы вокруг него (как если бы они были видимыми). Если false, правила интервалов, основанные на классах, игнорируются. Соответствует атрибуту OMML m:transp.

**Возвращаемое значение:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

Получает или задает значение, указывающее, является ли phantom прозрачным для правил интервалов, основанных на классах.

--------------------

Если true, операторы и символы внутри phantom все равно влияют на математические интервалы вокруг него (как если бы они были видимыми). Если false, правила интервалов, основанные на классах, игнорируются. Соответствует атрибуту OMML m:transp.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]