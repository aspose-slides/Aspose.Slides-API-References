---
title: SlideCollection
second_title: Справочник API Aspose.Slides для Android через Java
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
| [size()](#size--) | Возвращает количество элементов, фактически содержащихся в коллекции. |
| [get_Item(int index)](#get-Item-int-) | Возвращает элемент по указанному индексу. |
| [addClone(ISlide sourceSlide)](#addClone-com.aspose.slides.ISlide-) | Добавляет копию указанного слайда в конец коллекции. |
| [addClone(ISlide sourceSlide, ISection section)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ISection-) | Добавляет копию указанного слайда в конец указанного раздела. |
| [insertClone(int index, ISlide sourceSlide)](#insertClone-int-com.aspose.slides.ISlide-) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [addEmptySlide(ILayoutSlide layout)](#addEmptySlide-com.aspose.slides.ILayoutSlide-) | Добавляет новый пустой слайд в конец коллекции. |
| [insertEmptySlide(int index, ILayoutSlide layout)](#insertEmptySlide-int-com.aspose.slides.ILayoutSlide-) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [addClone(ISlide sourceSlide, ILayoutSlide destLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Добавляет копию указанного слайда в конец коллекции. |
| [insertClone(int index, ISlide sourceSlide, ILayoutSlide destLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.ILayoutSlide-) | Вставляет копию указанного слайда в указанную позицию коллекции. |
| [addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Добавляет копию указанного исходного слайда в конец коллекции. |
| [insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)](#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-) | Вставляет копию указанного исходного слайда в указанную позицию коллекции. |
| [remove(ISlide value)](#remove-com.aspose.slides.ISlide-) | Удаляет первое вхождение конкретного объекта из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по указанному индексу коллекции. |
| [iterator()](#iterator--) | Возвращает перечислитель, который проходит по элементам коллекции. |
| [iteratorJava()](#iteratorJava--) | Возвращает java-итератор для всей коллекции. |
| [toArray()](#toArray--) | Создаёт и возвращает массив со всеми слайдами. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Создаёт и возвращает массив со слайдами из указанного диапазона. |
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
| [isSynchronized()](#isSynchronized--) | Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). |
| [getSyncRoot()](#getSyncRoot--) | Возвращает объект синхронизации. |

### size() {#size--}
```
public final int size()
```

Возвращает количество элементов, фактически содержащихся в коллекции. Только для чтения int.

### get_Item(int index) {#get-Item-int-}
```
public final ISlide get_Item(int index)
```

Возвращает элемент по указанному индексу. Только для чтения [Slide](../../com.aspose.slides/slide).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide)

### addClone(ISlide sourceSlide) {#addClone-com.aspose.slides.ISlide-}
```
public final ISlide addClone(ISlide sourceSlide)
```

Добавляет копию указанного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |

--------------------

При клонировании слайда между разными презентациями мастер-слайда может быть также клонирован. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких клонов одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. Если требуется больший контроль над процессом клонирования, используйте \#addClone(ISlide,ILayoutSlide).addClone(ISlide,ILayoutSlide) или \#addClone(ISlide,IMasterSlide,boolean).addClone(ISlide,IMasterSlide,boolean) для клонирования слайдов, [IGlobalLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-) или [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) для клонирования макетов и [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) для клонирования мастеров. 

**Возвращаемое значение:**
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

**Возвращаемое значение:**
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
>  // Создать экземпляр класса Presentation, представляющего файл презентации
>  Presentation pres = new Presentation("CloneWithInSamePresentation.pptx");
>  try {
>      // Клонировать выбранный слайд в конец коллекции слайдов в той же презентации
>      ISlideCollection slds = pres.getSlides();
>      // Клонировать выбранный слайд в указанный индекс в той же презентации
>      slds.insertClone(2, pres.getSlides().get_Item(1));
>      // Сохранить изменённую презентацию на диск
>      pres.save("Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to clone at another position within Presentation.
>  
>  // Создать экземпляр класса Presentation для загрузки исходного файла презентации
>  Presentation srcPres = new Presentation("CloneAtEndOfAnother.pptx");
>  try {
>      // Создать экземпляр класса Presentation для целевого PPTX (куда будет клонирован слайд)
>      Presentation destPres = new Presentation();
>      try {
>          ISlideCollection slds = destPres.getSlides();
>          slds.insertClone(2, srcPres.getSlides().get_Item(0));
>          // Сохранить целевую презентацию на диск
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
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |

--------------------

При клонировании слайда между разными презентациями мастер-слайда может быть также клонирован. Внутренний реестр используется для отслеживания автоматически клонированных мастеров, чтобы предотвратить создание нескольких клонов одного и того же мастер-слайда. Ручное клонирование мастер-слайдов не будет ни предотвращено, ни зарегистрировано. Если требуется больший контроль над процессом клонирования, используйте \#insertClone(int,ISlide,ILayoutSlide).insertClone(int,ISlide,ILayoutSlide) или \#insertClone(int,ISlide,IMasterSlide,boolean).insertClone(int,ISlide,IMasterSlide,boolean) для клонирования слайдов и [IMasterSlideCollection.addClone(IMasterSlide)](../../com.aspose.slides/imasterslidecollection\#addClone-IMasterSlide-) для клонирования мастеров. 

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addEmptySlide(ILayoutSlide layout) {#addEmptySlide-com.aspose.slides.ILayoutSlide-}
```
public final ISlide addEmptySlide(ILayoutSlide layout)
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
public final ISlide insertEmptySlide(int index, ILayoutSlide layout)
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
public final ISlide addClone(ISlide sourceSlide, ILayoutSlide destLayout)
```

Добавляет копию указанного слайда в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Макет-слайд для нового слайда. |

**Возвращаемое значение:**
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
| destLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Макет-слайд для нового слайда. |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#addClone-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide addClone(ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Добавляет копию указанного исходного слайда в конец коллекции. При этом будет автоматически выбран соответствующий макет из указанного мастера (соответствующий макет — это макет с тем же Type или Name, что и у исходного слайда). Если соответствующего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout = false).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | boolean | Если в указанном мастере нет соответствующего макета, макет исходного слайда будет клонирован (при allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (при allowCloneMissingLayout = false). |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Новый слайд.

### insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout) {#insertClone-int-com.aspose.slides.ISlide-com.aspose.slides.IMasterSlide-boolean-}
```
public final ISlide insertClone(int index, ISlide sourceSlide, IMasterSlide destMaster, boolean allowCloneMissingLayout)
```

Вставляет копию указанного исходного слайда в указанную позицию коллекции. При этом будет автоматически выбран соответствующий макет из указанного мастера (соответствующий макет — это макет с тем же Type или Name, что и у исходного слайда). Если соответствующего макета нет, макет исходного слайда будет клонирован (если allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (если allowCloneMissingLayout = false).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Индекс нового слайда. |
| sourceSlide | [ISlide](../../com.aspose.slides/islide) | Слайд для клонирования. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Мастер-слайд для нового слайда. |
| allowCloneMissingLayout | boolean | Если в указанном мастере нет соответствующего макета, макет исходного слайда будет клонирован (при allowCloneMissingLayout = true) или будет выброшено исключение PptxEditException (при allowCloneMissingLayout = false). |

**Возвращаемое значение:**
[ISlide](../../com.aspose.slides/islide) - Вставленный слайд.

### remove(ISlide value) {#remove-com.aspose.slides.ISlide-}
```
public final void remove(ISlide value)
```

Удаляет первое вхождение конкретного объекта из коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISlide](../../com.aspose.slides/islide) | Слайд, который необходимо удалить из коллекции. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Удаляет элемент по указанному индексу коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс элемента, который необходимо удалить. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iterator()
```

Возвращает перечислитель, который проходит по элементам коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - IGenericEnumerator, который можно использовать для итерации по коллекции.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISlide> iteratorJava()
```

Возвращает java-итератор для всей коллекции.

**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISlide> - java.util.Iterator для всей коллекции.

### toArray() {#toArray--}
```
public final ISlide[] toArray()
```

Создаёт и возвращает массив со всеми слайдами.

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Массив [Slide](../../com.aspose.slides/slide)

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final ISlide[] toArray(int startIndex, int count)
```

Создаёт и возвращает массив со слайдами из указанного диапазона.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| startIndex | int | Индекс первого слайда для добавления. |
| count | int | Количество слайдов для добавления. |

**Возвращаемое значение:**
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

### reorder(int index, ISlide[] slides) {#reorder-int-com.aspose.slides.ISlide...-}
```
public final void reorder(int index, ISlide[] slides)
```

Перемещает слайды из коллекции в указанную позицию. Слайды будут размещены, начиная с указанного индекса, в порядке их появления в списке.

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

**Возвращаемое значение:**
int - Индекс слайда или -1, если слайд не принадлежит этой коллекции.

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

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromPdf(String path, PdfImportOptions pdfImportOptions) {#addFromPdf-java.lang.String-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(String path, PdfImportOptions pdfImportOptions)
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

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions) {#addFromPdf-java.io.InputStream-com.aspose.slides.PdfImportOptions-}
```
public final ISlide[] addFromPdf(InputStream pdfStream, PdfImportOptions pdfImportOptions)
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
| pdfStream | java.io.InputStream | Поток, который будет использоваться как источник PDF-документа |
| pdfImportOptions | [PdfImportOptions](../../com.aspose.slides/pdfimportoptions) | Параметры импорта PDF |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | java.lang.String | HTML-текст для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних ресурсов. Если параметр null, все внешние ресурсы будут игнорироваться. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### addFromHtml(String htmlText) {#addFromHtml-java.lang.String-}
```
public final ISlide[] addFromHtml(String htmlText)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | java.lang.String | HTML-текст для добавления. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] addFromHtml(InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Поток, который будет использоваться как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних ресурсов. Если параметр null, все внешние ресурсы будут игнорироваться. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### addFromHtml(InputStream htmlStream) {#addFromHtml-java.io.InputStream-}
```
public final ISlide[] addFromHtml(InputStream htmlStream)
```

Создаёт слайды из HTML-текста и добавляет их в конец коллекции.

--------------------

> ```
> // Создать экземпляр класса Presentation.
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("file.html");
>          // Вызвать метод AddFromHtml и передать HTML-файл.
>          pres.getSlides().addFromHtml(fos);
>          // Использовать метод Save для сохранения файла как PowerPoint-документ.
>          pres.save("MyPresentation.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | java.io.InputStream | Поток, который будет использоваться как источник HTML-файла. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | HTML-текст для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних ресурсов. Если параметр null, все внешние ресурсы будут игнорироваться. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | HTML-текст для добавления. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних ресурсов. Если параметр null, все внешние ресурсы будут игнорироваться. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | boolean | Флаг, определяющий, как начинать вставку: с нового слайда или с слайда по указанному индексу. Если **true**, вставка начинается с пустого места на слайде с указанным индексом. Если **false**, данные добавляются в созданные слайды. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### insertFromHtml(int index, String htmlText) {#insertFromHtml-int-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, String htmlText)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | HTML-текст для добавления. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, String htmlText, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlText | java.lang.String | HTML-текст для добавления. |
| useSlideWithIndexAsStart | boolean | Флаг, определяющий, как начинать вставку: с нового слайда или с слайда по указанному индексу. Если **true**, вставка начинается с пустого места на слайде с указанным индексом. Если **false**, данные добавляются в созданные слайды. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, который будет использоваться как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних ресурсов. Если параметр null, все внешние ресурсы будут игнорироваться. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-com.aspose.slides.IExternalResourceResolver-java.lang.String-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, IExternalResourceResolver resolver, String uri, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, который будет использоваться как источник HTML-файла. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-колбэк, используемый для получения внешних ресурсов. Если параметр null, все внешние ресурсы будут игнорироваться. |
| uri | java.lang.String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | boolean | Флаг, определяющий, как начинать вставку: с нового слайда или с слайда по указанному индексу. Если **true**, вставка начинается с пустого места на слайде с указанным индексом. Если **false**, данные добавляются в созданные слайды. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды.

### insertFromHtml(int index, InputStream htmlStream) {#insertFromHtml-int-java.io.InputStream-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, который будет использоваться как источник HTML-файла. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

### insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart) {#insertFromHtml-int-java.io.InputStream-boolean-}
```
public final ISlide[] insertFromHtml(int index, InputStream htmlStream, boolean useSlideWithIndexAsStart)
```

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанную позицию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Позиция для вставки. |
| htmlStream | java.io.InputStream | Поток, который будет использоваться как источник HTML-файла. |
| useSlideWithIndexAsStart | boolean | Флаг, определяющий, как начинать вставку: с нового слайда или с слайда по указанному индексу. Если **true**, вставка начинается с пустого места на слайде с указанным индексом. Если **false**, данные добавляются в созданные слайды. |

**Возвращаемое значение:**
com.aspose.slides.ISlide[] - Добавленные слайды

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

Возвращает значение, указывающее, синхронизирован ли доступ к коллекции (потокобезопасен). Только для чтения boolean.

**Возвращаемое значение:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Возвращает объект синхронизации. Только для чтения Object.

**Возвращаемое значение:**
java.lang.Object