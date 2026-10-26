---
title: SlideCollection
second_title: Справочник API Aspose.Slides для Java
description: Представляет коллекцию слайдов.
type: docs
url: /ru/com.aspose.slides/slidecollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.ISlideCollection](../../com.aspose.slides/islidecollection)
```
public final class SlideCollection extends DomObject<Presentation> implements ISlideCollection
```

Представляет коллекцию слайдов.
## Методы

| Метод | Описание |
| --- | --- |
| [size()](#size--) | Получает количество элементов, фактически содержащихся в коллекции. |
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
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу из коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по элементам коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми слайдами. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со всеми слайдами из указанного диапазона. |
| [reorder(int index, ISlide slide)](#reorder-int-com.aspose.slides.ISlide-) | Перемещает слайд из коллекции в указанную позицию. |
| [reorder(int index, ISlide[] slides)](#reorder-int-com.aspose.slides.ISlide...-) | Перемещает слайды из коллекции в указанную позицию. |
| [indexOf(ISlide slide)](#indexOf-com.aspose.slides.ISlide-) | Возвращает индекс указанного слайда в коллекции. |
| [addFromPdf(String path)](#addFromPdf-java.lang.String-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [addFromPdf(String path, PdfImportOptions pdfImportOptions)](#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF. |
| [addFromPdf(InputStream pdfStream)](#addFromPdf-java.io.InputStream-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)](#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-) | Создаёт слайды из PDF-документа и добавляет их в конец коллекции. |
| [addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [addFromHtml(String htmlText)](#addFromHtml-java.lang.String-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [addFromHtml(InputStream htmlStream)](#addFromHtml-java.io.InputStream-) | Создаёт слайды из HTML-текста и добавляет их в конец коллекции. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, String htmlText)](#insertFromHtml-int-java.lang.String-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.lang.String-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream)](#insertFromHtml-int-java.io.InputStream-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)](#insertFromHtml-int-java.io.InputStream-boolean-) | Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Копирует все элементы из коллекции в указанный массив. |
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, является ли доступ к коллекции синхронизированным (потокобезопасным). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |

### size() {#size--}
```
public final int size()
```

Получает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

**Возвращает:**
int

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Получает элемент по указанному индексу. Только для чтения [Slide](../../com.aspose.slides/slide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Добавляет копию указанного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования.

--------------------

При клонировании слайда между разными презентациями может быть клонирована и мастер-страница слайда. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастера. Ручное клонирование мастер-страниц не предотвращается и не регистрируется. Если требуется больший контроль над процессом клонирования, используйте \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) или \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) для клонирования слайдов, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) или [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) для клонирования раскладок и [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) для клонирования мастеров. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### addClone(ISlide sourceSlide, ISection section) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-}
```
public final ISlide addClone(ISlide sourceSlide, ISection section)
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
>      // Теперь второй раздел содержит копию первого слайда.
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| section | [ISection](../../com.aspose.slides/isection) | Раздел для нового слайда. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide) {#insertClone-int-com.aspose.slides.ISlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide)
```

Вставляет копию указанного слайда в указанную позицию коллекции.

--------------------

> ```
> The following example shows how to clone at another position within Presentation.
>  
>  // Создайте объект класса Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Клонируйте выбранный слайд в конец коллекции слайдов в той же презентации
>      ISlideCollection slds = pres.getSlides();
>      // Клонируйте выбранный слайд в указанный индекс в той же презентации
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Запишите изменённую презентацию на диск
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Создайте объект класса Presentation для загрузки исходного файла презентации
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Создайте объект класса Presentation для целевого PPTX (куда будет склонирован слайд)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Запишите целевую презентацию на диск
>          destPres.save("Aspose2_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (destPres != null) destPres.dispose();
>      }
>  } finally {
>      if (srcPres != null) srcPres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования.

--------------------

При клонировании слайда между разными презентациями может быть клонирована и мастер-страница слайда. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких копий одного и того же мастера. Ручное клонирование мастер-страниц не предотвращается и не регистрируется. Если требуется больший контроль над процессом клонирования, используйте \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) или \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) для клонирования слайдов и [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) для клонирования мастеров. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
```

Добавляет новый пустой слайд в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Раскладка для слайда. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Добавленный слайд.

### insertEmptySlide(int index, ILayoutSlide layout) {#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
```

Вставляет копию указанного слайда в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| layout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Раскладка для слайда. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addClone(ISlide sourceSlide, ILayoutSlide destLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Добавляет копию указанного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Раскладка для нового слайда. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)
```

Вставляет копию указанного слайда в указанную позицию коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Раскладка для нового слайда. |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Добавляет копию указанного исходного слайда в конец коллекции. Подходящая раскладка будет автоматически выбрана из указанного мастера (подходящая раскладка — это раскладка с тем же типом или именем, что и у исходного слайда). Если подходящей раскладки нет, раскладка исходного слайда будет клонирована (если allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout = false).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-страница для нового слайда. |
| allowCloneMissingLayout | boolean | Если в указанном мастере нет подходящей раскладки, раскладка исходного слайда будет клонирована (если allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout = false). |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Вставляет копию указанного исходного слайда в указанную позицию коллекции. Подходящая раскладка будет автоматически выбрана из указанного мастера (подходящая раскладка — это раскладка с тем же типом или именем, что и у исходного слайда). Если подходящей раскладки нет, раскладка исходного слайда будет клонирована (если allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout = false).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-страница для нового слайда. |
| allowCloneMissingLayout | boolean | Если в указанном мастере нет подходящей раскладки, раскладка исходного слайда будет клонирована (если allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout = false). |

**Возвращает:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Удаляет первое вхождение указанного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Слайд, удаляемый из коллекции. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который необходимо удалить. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Возвращает перечислитель, который проходит по элементам коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator, который можно использовать для обхода коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращает:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator для всей коллекции.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Создаёт и возвращает массив со всеми слайдами.

**Возвращает:**
com.aspose.slides.ISlide[] - Массив [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив со всеми слайдами из указанного диапазона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого слайда для добавления. |
| count | int | Количество слайдов для добавления. |

**Возвращает:**
com.aspose.slides.ISlide[] - Массив [Slide](../../com.aspose.slides/slide)
### reorder(int index, ISlide slide) {#reorder-int-com.aspose.slides.ISlide-}
```
public final void reorder(int index, ISlide slide)
```

Перемещает слайд из коллекции в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Целевой индекс. |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд для перемещения. |

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISSlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Перемещает слайды из коллекции в указанную позицию. Слайды будут размещены, начиная с индекса, в порядке их появления в списке.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Целевой индекс. |
| slides | [ISlide\[\]](../../com.aspose.slides/islide) | Слайды для перемещения. |

### indexOf(ISlide slide) {#indexOf-com.aspose.slides.ISlide-}
```
public final int indexOf(ISlide slide)
```

Возвращает индекс указанного слайда в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Слайд для поиска. |

**Возвращает:**
int - Индекс слайда или -1, если слайда нет в этой коллекции.

### addFromPdf(String path) {#addFromPdf-java.lang.String-}
```
public final ISlide[] addFromPdf(String path)
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

**Возвращает:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции с учётом параметров импорта PDF.

--------------------

> ```
> Example:
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

**Возвращает:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromPdf(InputStream pdfStream) {#addFromPdf-java.io.InputStream-}
```
public final ISlide[] addFromPdf(InputStream pdfStream)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции.

--------------------

> ```
> Пример:
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
| pdfStream | java.io.InputStream | Поток, который будет использоваться как источник PDF-документа |

**Возвращает:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
```

Создаёт слайды из PDF-документа и добавляет их в конец коллекции.

--------------------

> ```
> Пример:
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
| pdfStream | java.io.InputStream | Поток, который будет использоваться как источник PDF-документа |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Параметры импорта PDF |

**Возвращает:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | java.lang.String | HTML для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-обратный вызов для получения внешних ресурсов. Если параметр null, все внешние ресурсы игнорируются. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращает:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | java.lang.String | HTML для добавления. |

**Возвращает:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Объект-поток, который будет использоваться как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-обратный вызов для получения внешних ресурсов. Если параметр null, все внешние ресурсы игнорируются. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

--------------------

> ```
> // Создайте экземпляр класса Presentation.
>  Presentation pres = new Presentation();
>  try {
>      String html = new String(Files.readAllBytes(Paths.get("file.html")));
>      // Вызовите метод AddFromHtml и передайте HTML-файл.
>      pres.getSlides().addFromHtml(html);
>      // Используйте метод Save, чтобы сохранить файл как документ PowerPoint.
>      pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Объект-поток, который будет использоваться как источник HTML-файла. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlText | java.lang.String | HTML для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-обратный вызов для получения внешних ресурсов. Если параметр null, все внешние ресурсы игнорируются. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlText | java.lang.String | HTML для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-обратный вызов для получения внешних ресурсов. Если параметр null, все внешние ресурсы игнорируются. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства в слайде с указанным индексом. Если **false**, данные будут добавлены к создаваемым слайдам. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlText | java.lang.String | HTML для добавления. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlText | java.lang.String | HTML для добавления. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства в слайде с указанным индексом. Если **false**, данные будут добавлены к создаваемым слайдам. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlStream | java.io.InputStream | Объект-поток, который будет использоваться как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-обратный вызов для получения внешних ресурсов. Если параметр null, все внешние ресурсы игнорируются. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlStream | java.io.InputStream | Объект-поток, который будет использоваться как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-обратный вызов для получения внешних ресурсов. Если параметр null, все внешние ресурсы игнорируются. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства в слайде с указанным индексом. Если **false**, данные будут добавлены к создаваемым слайдам. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlStream | java.io.InputStream | Объект-поток, который будет использоваться как источник HTML-файла. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция вставки. |
| htmlStream | java.io.InputStream | Объект-поток, который будет использоваться как источник HTML-файла. |
| useSlideWithIndexAsStart | boolean | Этот флаг определяет, как начинать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства в слайде с указанным индексом. Если **false**, данные будут добавлены к создаваемым слайдам. |

**Возвращает:**
com.aspose.slides.ISSlide[] - Добавленные слайды

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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасный). Тoлько для чтения boolean.

**Возвращает:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Тoлько для чтения Object.

**Возвращает:**
java.lang.Object