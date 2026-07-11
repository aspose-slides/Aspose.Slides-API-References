---
title: ISlideCollection
second_title: Справочник API Aspose.Slides для Android через Java
description: Представляет коллекцию слайдов.
type: docs
url: /ru/com.aspose.slides/islidecollection/
---
**Все реализованные интерфейсы:**
com.aspose.slides.IGenericCollection
```
public interface ISlideCollection extends IGenericCollection<ISlide>
```

Представляет коллекцию слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по указанному индексу. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Добавляет копию указанного слайда в конец коллекции. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Добавляет копию указанного слайда в конец указанного раздела. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Добавляет новый пустой слайд в конец коллекции. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Добавляет копию указанного слайда в конец коллекции. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Добавляет копию указанного исходного слайда в конец коллекции. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Удаляет первое вхождение указанного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу в коллекции. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми слайдами. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со всеми слайдами из указанного диапазона. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Перемещает слайд из коллекции в указанную позицию. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Перемещает слайды из коллекции в указанную позицию. Слайды будут размещены, начиная с индекса, в порядке их появления в список. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Возвращает индекс указанного слайда в коллекции. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ISlide get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [ISlide](../../com.aspose.slides/islide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public abstract ISlide addClone(ISlide sourceSlide)
```

Добавляет копию указанного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |

--------------------

При клонировании слайда между различными презентациями мастер-слайда также может быть клонирован. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастера-слайда. Ручное клонирование мастеров слайдов не будет ни предотвращено, ни зарегистрировано. Если вам нужен больший контроль над процессом клонирования, используйте \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) или \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) для клонирования слайдов, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) или [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) для клонирования макетов и [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) для клонирования мастеров.

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public abstract ISlide addClone(ISlide sourceSlide, ISection section)
```

Добавляет копию указанного слайда в конец указанного раздела.

--------------------

> ```
> IPresentation presentation = new Presentation();
>  try
>  {
>      presentation.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 200, 50, 300, 100);
>      presentation.getSections().addSection("Section 1", presentation.getSlides().get_Item(0));
>      
>      ISection section2 = presentation.getSections().appendEmptySection("Section 2");
>      presentation.getSlides().addClone(presentation.getSlides().get_Item(0), section2);
>      
>      // Теперь во второй секции содержится копия первого слайда.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для нового слайда. |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide)
```

Вставляет копию указанного слайда в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |

--------------------

При клонировании слайда между различными презентациями мастер-слайда также может быть клонирован. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастера-слайда. Ручное клонирование мастеров слайдов не будет ни предотвращено, ни зарегистрировано. Если вам нужен больший контроль над процессом клонирования, используйте \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) или \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) для клонирования слайдов и [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) для клонирования мастеров.

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addEmptySlide(ILayoutSlide layout)
```

Добавляет новый пустой слайд в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Макет для слайда. |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Добавленный слайд.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Вставляет копию указанного слайда в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Макет для слайда. |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Добавляет копию указанного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Макет слайда для нового слайда. |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Вставляет копию указанного слайда в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Макет слайда для нового слайда. |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Добавляет копию указанного исходного слайда в конец коллекции. Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | boolean | Если в указанном мастере нет подходящего макета, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public abstract ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Вставляет копию указанного исходного слайда в указанную позицию коллекции. Подходящий макет будет выбран автоматически из указанного мастера (подходящий макет — это макет с тем же типом или именем, что и макет исходного слайда). Если подходящего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | boolean | Если в указанном мастере нет подходящего макета, макет исходного слайда будет клонирован (если allowCloneMissingLayout равно true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout равно false). |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public abstract void remove(ISlide value)
```

Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Слайд, который нужно удалить из коллекции. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по указанному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой базовый индекс элемента для удаления. |

### toArray() {#toArray--}
```
public abstract ISlide[] toArray()
```

Создаёт и возвращает массив со всеми слайдами.

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract ISlide[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив со всеми слайдами из указанного диапазона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого слайда для добавления. |
| count | int | Количество слайдов для добавления. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)

### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public abstract void reorder(int index, ISlide slide)
```

Перемещает слайд из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Целевой индекс. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд для перемещения. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public abstract void reorder(int index, ISlide[] slides)
```

Перемещает слайды из коллекции в указанную позицию. Слайды будут размещены, начиная с индекса, в порядке их появления в список.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Целевой индекс. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Слайды для перемещения. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public abstract int indexOf(ISlide slide)
```

Возвращает индекс указанного слайда в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд для поиска. |

**Возвращаемое значение:**
int - Index of a slide or -1 if slide not from this collection.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public abstract ISlide[] addFromPdf(String path)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции.

--------------------

> ```
> Пример:
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getSlides().addFromPdf("document.pdf");
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь к PDF-документу |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF.

--------------------

> ```
> Пример:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
>      pres.getSlides().addFromPdf("document.pdf", pdfImportOptions);
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь к PDF-документу |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Параметры импорта PDF |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream, pdfImportOptions);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Поток, используемый как источник PDF-документа |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Параметры импорта PDF |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public abstract ISlide[] addFromPdf(InputStream pdfStream)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream stream = new FileInputStream("document.pdf");
>      pres.getSlides().addFromPdf(stream);
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pdfStream | java.io.InputStream | Поток, используемый как источник PDF-документа |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | java.lang.String | Html для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбэк, используемый для получения внешних объектов. Если параметр null, все внешние объекты будут игнорированы. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public abstract ISlide[] addFromHtml(String htmlText)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | java.lang.String | Html для добавления. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Поток, используемый как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбэк, используемый для получения внешних объектов. Если параметр null, все внешние объекты будут игнорированы. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public abstract ISlide[] addFromHtml(InputStream htmlStream)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Поток, используемый как источник HTML-файла. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | Html для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбэк, используемый для получения внешних объектов. Если параметр null, все внешние объекты будут игнорированы. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | Html для добавления. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, используемый как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбэк, используемый для получения внешних объектов. Если параметр null, все внешние объекты будут игнорированы. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, используемый как источник HTML-файла. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | Html для добавления. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | Html для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбэк, используемый для получения внешних объектов. Если параметр null, все внешние объекты будут игнорированы. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides.

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, используемый как источник HTML-файла. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public abstract ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, используемый как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбэк, используемый для получения внешних объектов. Если параметр null, все внешние объекты будут игнорированы. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Added slides.