---
title: InsertFromHtml
second_title: Aspose.Sildes para referencia de API .NET
description: Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.
type: docs
weight: 140
url: /es/aspose.slides/slidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlText | String | Html a añadir. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Usado para resolver enlaces relativos. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlText | String | Html a añadir. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Usado para resolver enlaces relativos. |
| useSlideWithIndexAsStart | Boolean | Esta bandera determina cómo comenzar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará desde un espacio vacío en la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlText | String | Html a añadir. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlText | String | Html a añadir. |
| useSlideWithIndexAsStart | Boolean | Esta bandera determina cómo comenzar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará desde un espacio vacío en la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlReader | TextReader | Objeto TextReader que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Usado para resolver enlaces relativos. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlReader | TextReader | Objeto TextReader que se utilizará como fuente de un archivo HTML. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Usado para resolver enlaces relativos. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| resolver | IExternalResourceResolver | Un objeto de callback utilizado para obtener objetos externos. Si este parámetro es nulo, todos los objetos externos serán ignorados. |
| uri | String | Un URI del HTML especificado. Usado para resolver enlaces relativos. |
| useSlideWithIndexAsStart | Boolean | Esta bandera determina cómo comenzar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará desde un espacio vacío en la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Crea diapositivas a partir de texto HTML y las inserta en la colección en la posición especificada.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | Int32 | Posición para insertar. |
| htmlStream | Stream | Un objeto Stream que se utilizará como fuente de un archivo HTML. |
| useSlideWithIndexAsStart | Boolean | Esta bandera determina cómo comenzar la inserción: desde una nueva diapositiva o desde la diapositiva con el índice especificado. Si **true**, la inserción de datos comenzará desde un espacio vacío en la diapositiva con el índice especificado. Si **false**, los datos se añadirán a las diapositivas creadas. |

### Valor de retorno

Diapositivas añadidas.

### Véase también

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->