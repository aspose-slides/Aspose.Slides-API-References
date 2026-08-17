---
title: Presentation
second_title: Справочная документация API Aspose.Slides for Java
description: Представляет презентацию Microsoft PowerPoint.
type: docs
url: /ru/com.aspose.slides/presentation/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPresentation](../../com.aspose.slides/ipresentation), com.aspose.slides.IDOMObject
```
public final class Presentation implements IPresentation, IDOMObject
```

Представляет презентацию Microsoft PowerPoint.

--------------------

> ```
> The following example shows how to create PowerPoint Presentation.
>   
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation pres = new Presentation();
>  try {
>      // Получить первый слайд
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Добавить автофигуру типа линия
>      slide.getShapes().addAutoShape(ShapeType.Line, 50, 150, 300, 0);
>      // Сохранить файл презентации.
>      pres.save("NewPresentation_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>   
>   The following example shows how to open and save Presentation.
>   
>  // Загрузить любой поддерживаемый файл в Presentation, напр., ppt, pptx, odp и др.
>  Presentation pres = new Presentation("Sample.odp");
>  try {
>      // Сохранить файл презентации.
>      pres.save("OutputPresenation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Presentation()](#Presentation--) | Этот конструктор создает новую презентацию с нуля. |
| [Presentation(LoadOptions loadOptions)](#Presentation-com.aspose.slides.LoadOptions-) | Этот конструктор создает новую презентацию с нуля. |
| [Presentation(InputStream stream)](#Presentation-java.io.InputStream-) | Этот конструктор является основным механизмом чтения существующей презентации. |
| [Presentation(InputStream stream, LoadOptions loadOptions)](#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-) | Этот конструктор является основным механизмом чтения существующей презентации. |
| [Presentation(String file)](#Presentation-java.lang.String-) | Этот конструктор получает путь к исходному файлу, из которого читается содержимое презентации. |
| [Presentation(String file, LoadOptions loadOptions)](#Presentation-java.lang.String-com.aspose.slides.LoadOptions-) | Этот конструктор получает путь к исходному файлу, из которого читается содержимое презентации. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Возвращает или задает дату и время, которые заменят содержимое полей даты и времени. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Возвращает или задает дату и время, которые заменят содержимое полей даты и времени. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает текущий менеджер HeaderFooter. |
| [getProtectionManager()](#getProtectionManager--) | Получает менеджер прав доступа для этой презентации. |
| [getSlides()](#getSlides--) | Возвращает список всех слайдов, определенных в презентации. |
| [getSections()](#getSections--) | Возвращает список всех секций слайдов, определенных в презентации. |
| [getSlideSize()](#getSlideSize--) | Возвращает объект размера слайда. |
| [getNotesSize()](#getNotesSize--) | Возвращает объект размера слайда заметок. |
| [getLayoutSlides()](#getLayoutSlides--) | Возвращает список всех шаблонов слайдов, определенных в презентации. |
| [getMasters()](#getMasters--) | Возвращает список всех мастер-слайдов, определенных в презентации. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Возвращает менеджер мастера заметок. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Возвращает менеджер мастера раздаточных материалов. |
| [getFontsManager()](#getFontsManager--) | Возвращает менеджер шрифтов. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Возвращает стиль текста по умолчанию для фигур. |
| [getCommentAuthors()](#getCommentAuthors--) | Возвращает коллекцию авторов комментариев. |
| [getDocumentProperties()](#getDocumentProperties--) | Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа. |
| [getImages()](#getImages--) | Возвращает коллекцию всех изображений в презентации. |
| [getAudios()](#getAudios--) | Возвращает коллекцию всех встроенных аудиофайлов в презентации. |
| [getVideos()](#getVideos--) | Возвращает коллекцию всех встроенных видеофайлов в презентации. |
| [getSlideShowSettings()](#getSlideShowSettings--) | Возвращает настройки слайд-шоу для презентации. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Возвращает коллекцию подписей, использованных для подписи презентации. |
| [getCustomData()](#getCustomData--) | Возвращает пользовательские данные презентации. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Возвращает все части пользовательских данных в презентации. |
| [getVbaProject()](#getVbaProject--) | Получает или задает проект VBA с макросами презентации. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Получает или задает проект VBA с макросами презентации. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Обеспечивает простой доступ ко всем гиперссылкам, содержащимся во всех слайдах презентации (не в мастер-, шаблонных и слайдах заметок). |
| [getViewProperties()](#getViewProperties--) | Получает свойства просмотра, применимые ко всей презентации. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Представляет номер первого слайда в презентации |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Представляет номер первого слайда в презентации |
| [getSensitivityLabels()](#getSensitivityLabels--) | Возвращает коллекцию меток чувствительности, примененных к документу презентации. |
| [getSlideById(long id)](#getSlideById-long-) | Возвращает Slide, MasterSlide или LayoutSlide по идентификатору. |
| [getSourceFormat()](#getSourceFormat--) | Возвращает информацию о формате, из которого была загружена презентация. |
| [getMasterTheme()](#getMasterTheme--) | Возвращает мастер-тему. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Сохраняет все слайды презентации в файл в указанном формате. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Сохраняет все слайды презентации в поток в указанном формате. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Сохраняет все слайды презентации в файл в указанном формате с дополнительными параметрами. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Сохраняет все слайды презентации в поток в указанном формате с дополнительными параметрами. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Возвращает объекты Image для всех слайдов презентации. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Возвращает объекты Thumbnail Image для указанных слайдов презентации. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием. |
| [getImages(IRenderingOptions options, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером. |
| [getImages(IRenderingOptions options, int[] slides, Dimension imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Сохраняет указанные слайды презентации в файл в указанном формате с сохранением номеров страниц. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Сохраняет указанные слайды презентации в файл в указанном формате с сохранением номеров страниц. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Сохраняет указанные слайды презентации в поток в указанном формате с сохранением номеров страниц. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет фрагменты текста с одинаковым форматированием во всех абзацах всех приемлемых фигур на всех слайдах. |
| [dispose()](#dispose--) | Освобождает все ресурсы, используемые этим объектом Presentation. |
| [getPresentation()](#getPresentation--) | Возвращает родительскую презентацию текста. |
| [highlightText(String text, Color highlightColor)](#highlightText-java.lang.String-java.awt.Color-) | Выделяет все совпадения образца текста указанным цветом. |
| [highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Выделяет все совпадения образца текста указанным цветом. |
| [highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Заменяет все совпадения регулярного выражения указанной строкой. |
### Presentation() {#Presentation--}
```
public Presentation()
```

Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд.

### Presentation(LoadOptions loadOptions) {#Presentation-com.aspose.slides.LoadOptions-}
```
public Presentation(LoadOptions loadOptions)
```

Этот конструктор создает новую презентацию с нуля. Созданная презентация содержит один пустой слайд.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Дополнительные параметры загрузки. |

### Presentation(InputStream stream) {#Presentation-java.io.InputStream-}
```
public Presentation(InputStream stream)
```

Этот конструктор является основным механизмом чтения существующей презентации.

--------------------

> ```
> FileInputStream fis = new FileInputStream("demo.pptx");
>  Presentation pres = new Presentation(fis);
>  fis.close();
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток. |

### Presentation(InputStream stream, LoadOptions loadOptions) {#Presentation-java.io.InputStream-com.aspose.slides.LoadOptions-}
```
public Presentation(InputStream stream, LoadOptions loadOptions)
```

Этот конструктор является основным механизмом чтения существующей презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Входной поток. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Дополнительные параметры загрузки. |

### Presentation(String file) {#Presentation-java.lang.String-}
```
public Presentation(String file)
```

Этот конструктор получает путь к исходному файлу, из которого читается содержимое презентации.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Входной файл. |

### Presentation(String file, LoadOptions loadOptions) {#Presentation-java.lang.String-com.aspose.slides.LoadOptions-}
```
public Presentation(String file, LoadOptions loadOptions)
```

Этот конструктор получает путь к исходному файлу, из которого читается содержимое презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| file | java.lang.String | Входной файл. |
| loadOptions | [LoadOptions](../../com.aspose.slides/loadoptions) | Дополнительные параметры загрузки. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public final Date getCurrentDateTime()
```

Возвращает или задает дату и время, которые заменят содержимое полей даты и времени. По умолчанию – время создания этого объекта Presentation. Чтение/запись java.util.Date.

**Возвращаемое значение:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public final void setCurrentDateTime(Date value)
```

Возвращает или задает дату и время, которые заменят содержимое полей даты и времени. По умолчанию – время создания этого объекта Presentation. Чтение/запись java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IPresentationHeaderFooterManager getHeaderFooterManager()
```

Возвращает текущий менеджер HeaderFooter. Только для чтения [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

--------------------

> ```
> The following example shows how to set footer visibility inside Slide of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IBaseSlideHeaderFooterManager headerFooterManager = pres.getSlides().get_Item(0).getHeaderFooterManager();
>      if (!headerFooterManager.isFooterVisible()) // Свойство IsFooterVisible используется для указания, что плейсхолдер нижнего колонтитула слайда отсутствует.
>      {
>          headerFooterManager.setFooterVisibility(true); // Метод SetFooterVisibility используется для того, чтобы сделать плейсхолдер нижнего колонтитула слайда видимым.
>      }
>      if (!headerFooterManager.isSlideNumberVisible()) // Свойство IsSlideNumberVisible используется для указания, что плейсхолдер номера слайда отсутствует.
>      {
>          headerFooterManager.setSlideNumberVisibility(true); // Метод SetSlideNumberVisibility используется для того, чтобы сделать плейсхолдер номера слайда видимым.
>      }
>      if (!headerFooterManager.isDateTimeVisible()) // Свойство IsDateTimeVisible используется для указания, что плейсхолдер даты и времени слайда отсутствует.
>      {
>          headerFooterManager.setDateTimeVisibility(true); // Метод SetFooterVisibility используется для того, чтобы сделать плейсхолдер даты и времени слайда видимым.
>      }
>      headerFooterManager.setFooterText("Footer text"); // Метод SetFooterText используется для установки текста в плейсхолдер нижнего колонтитула слайда.
>      headerFooterManager.setDateTimeText("Date and time text"); // Метод SetDateTimeText используется для установки текста в плейсхолдер даты и времени слайда.
>      pres.save("Presentation.ppt", SaveFormat.Ppt);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set child footer visibility inside Slide.
>  
>  Presentation pres = new Presentation("presentation.ppt");
>  try
>  {
>      IMasterSlideHeaderFooterManager headerFooterManager = pres.getMasters().get_Item(0).getHeaderFooterManager();
>      headerFooterManager.setFooterAndChildFootersVisibility(true); // Метод SetFooterAndChildFootersVisibility используется для того, чтобы сделать видимыми мастер-слайд и все дочерние плейсхолдеры нижних колонтитулов.
>      headerFooterManager.setSlideNumberAndChildSlideNumbersVisibility(true); // Метод SetSlideNumberAndChildSlideNumbersVisibility используется для того, чтобы сделать видимыми мастер-слайд и все дочерние плейсхолдеры номеров страниц.
>      headerFooterManager.setDateTimeAndChildDateTimesVisibility(true); // Метод SetDateTimeAndChildDateTimesVisibility используется для того, чтобы сделать видимыми мастер-слайд и все дочерние плейсхолдеры даты и времени.
> 
>      headerFooterManager.setFooterAndChildFootersText("Footer text"); // Метод SetFooterAndChildFootersText используется для установки текста в мастер-слайд и все дочерние плейсхолдеры нижних колонтитулов.
>      headerFooterManager.setDateTimeAndChildDateTimesText("Date and time text"); // Метод SetDateTimeAndChildDateTimesText используется для установки текста в мастер-слайд и все дочерние плейсхолдеры даты и времени.
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public final IProtectionManager getProtectionManager()
```

Получает менеджер прав доступа для этой презентации. Только для чтения [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Возвращаемое значение:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public final ISlideCollection getSlides()
```

Возвращает список всех слайдов, определенных в презентации. Только для чтения [ISlideCollection](../../com.aspose.slides/islidecollection).

--------------------

> ```
> The following example shows how to set slides' background color of PowerPoint Presentation.
>  
>  // Создать объект класса Presentation, представляющий файл презентации
>  Presentation pres = new Presentation();
>  try
>  {
>      // Установить цвет фона первого ISlide в синий
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.BLUE);
>      pres.save("ContentBG_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slides' background image of PowerPoint Presentation.
>  
>  // Создать объект класса Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("SetImageAsBackground.pptx");
>  try {
>      // Установить фон с изображением
>      pres.getSlides().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Picture);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().setPictureFillMode(PictureFillMode.Stretch);
>      // Установить изображение
>      BufferedImage img = ImageIO.read(new File("Tulips.jpg"));
>      // Добавить изображение в коллекцию изображений презентации
>      IPPImage imgx = pres.getImages().addImage(img);
>      pres.getSlides().get_Item(0).getBackground().getFillFormat().getPictureFillFormat().getPicture().setImage(imgx);
>      // Записать презентацию на диск
>      pres.save("ContentBG_Img_out.pptx", SaveFormat.Pptx);
>  } catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add slide transition Presentation.
>  
>  // Создать объект класса Presentation для загрузки исходного файла презентации
>  Presentation pres = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Применить переход типа круг к слайду 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Применить переход типа гребёнка к слайду 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Записать презентацию на диск
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to add advanced slide Transition.
>  
>  // Создать объект класса Presentation, представляющий файл презентации
>  Presentation pres = new Presentation("BetterSlideTransitions.pptx");
>  try
>  {
>      // Применить переход типа круг к слайду 1
>      pres.getSlides().get_Item(0).getSlideShowTransition().setType(TransitionType.Circle);
>      // Установить время перехода 3 секунды
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(0).getSlideShowTransition().setAdvanceAfterTime(3000);
>      // Применить переход типа гребёнка к слайду 2
>      pres.getSlides().get_Item(1).getSlideShowTransition().setType(TransitionType.Comb);
>      // Установить время перехода 5 секунд
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(1).getSlideShowTransition().setAdvanceAfterTime(5000);
>      // Применить переход типа зум к слайду 3
>      pres.getSlides().get_Item(2).getSlideShowTransition().setType(TransitionType.Zoom);
>      // Установить время перехода 7 секунд
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceOnClick(true);
>      pres.getSlides().get_Item(2).getSlideShowTransition().setAdvanceAfterTime(7000);
>      // Записать презентацию на диск
>      pres.save("SampleTransition_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public final ISectionCollection getSections()
```

Возвращает список всех секций слайдов, определенных в презентации. Только для чтения [ISectionCollection](../../com.aspose.slides/isectioncollection).

--------------------

> ```
> The following examples shows how to create Sections in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide defaultSlide = pres.getSlides().get_Item(0);
>      ISlide newSlide1 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide2 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide3 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISlide newSlide4 = pres.getSlides().addEmptySlide(pres.getLayoutSlides().get_Item(0));
>      ISection section1 = pres.getSections().addSection("Section 1", newSlide1);
>      // section1 будет завершён на newSlide2, а после него начнётся section2
>      ISection section2 = pres.getSections().addSection("Section 2", newSlide3);
>      pres.save("pres-sections.pptx", SaveFormat.Pptx);
>      pres.getSections().reorderSectionWithSlides(section2, 0);
>      pres.save("pres-sections-moved.pptx", SaveFormat.Pptx);
>      pres.getSections().removeSectionWithSlides(section2);
>      pres.getSections().appendEmptySection("Last empty section");
>      pres.save("pres-section-with-empty.pptx",SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to changing the names of Sections.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISection section = pres.getSections().get_Item(0);
>      section.setName("My section");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public final ISlideSize getSlideSize()
```

Возвращает объект размера слайда. Только для чтения [ISlideSize](../../com.aspose.slides/islidesize).

--------------------

> ```
> The following example shows how to change the slide size in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres-4x3-aspect-ratio.pptx");
>  try {
>      pres.getSlideSize().setSize(SlideSizeType.OnScreen16x9, SlideSizeScaleType.DoNotScale);
>      pres.save("pres-4x3-aspect-ratio.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to set slide size with respect to content scaling for a PowerPoint Presentation.
>  
>  // Создать объект Presentation, представляющий файл презентации
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation auxPresentation = new Presentation();
>      try {
>          ISlide slide = presentation.getSlides().get_Item(0);
>          // Установить размер слайдов сгенерированных презентаций согласно источнику
>          presentation.getSlideSize().setSize(540, 720, SlideSizeScaleType.EnsureFit); // Метод SetSize используется для установки размера слайда с масштабированием содержимого для обеспечения его вписывания
>          presentation.getSlideSize().setSize(SlideSizeType.A4Paper, SlideSizeScaleType.Maximize); // Метод SetSize используется для установки размера слайда с максимизацией размера содержимого
>          // Сохранить презентацию на диск
>          auxPresentation.save("Set_Size&Type_out.pptx", SaveFormat.Pptx);
>      } finally {
>          if (auxPresentation != null) auxPresentation.dispose();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
>  
>  The following example shows how to specifying custom slide sizes in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getSlideSize().setSize(780, 540, SlideSizeScaleType.DoNotScale); // Размер бумаги A4
>      pres.save("pres-a4-slide-size.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public final INotesSize getNotesSize()
```

Возвращает объект размера слайда заметок. Только для чтения [INotesSize](../../com.aspose.slides/inotessize).

**Возвращаемое значение:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IGlobalLayoutSlideCollection getLayoutSlides()
```

Возвращает список всех шаблонов слайдов, определенных в презентации. Только для чтения [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Вы можете получить доступ к альтернативному API для добавления/вставки/удаления/клонирования шаблонов слайдов, используя свойство IMasterSlide.LayoutSlides.

**Возвращаемое значение:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public final IMasterSlideCollection getMasters()
```

Возвращает список всех мастер-слайдов, определенных в презентации. Только для чтения [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

--------------------

> ```
> The following examples shows how to adding Images to Master Slides of PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IMasterSlide masterSlide = slide.getLayoutSlide().getMasterSlide();
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      masterSlide.getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to change the background color of the master slide of PowerPoint Presentation.
>  
>  // Создать объект класса Presentation, представляющий файл презентации
>  Presentation pres = new Presentation();
>  try
>  {
>      // Установить цвет фона мастер-слайда ISlide в Forest Green
>      pres.getMasters().get_Item(0).getBackground().setType(BackgroundType.OwnBackground);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().setFillType(FillType.Solid);
>      pres.getMasters().get_Item(0).getBackground().getFillFormat().getSolidFillColor().setColor(Color.GREEN);
>      // Записать презентацию на диск
>      pres.save("SetSlideBackgroundMaster_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add slide layout to PowerPoint Presentation.
>  
>  // Создать объект класса Presentation, представляющий файл презентации
>  Presentation presentation = new Presentation("AccessSlides.pptx");
>  try
>  {
>      // Попытаться найти по типу макета слайда
>      IMasterLayoutSlideCollection layoutSlides = presentation.getMasters().get_Item(0).getLayoutSlides();
>      ILayoutSlide layoutSlide = null;
>      if (layoutSlides.getByType(SlideLayoutType.TitleAndObject) != null)
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.TitleAndObject);
>      else
>          layoutSlide = layoutSlides.getByType(SlideLayoutType.Title);
> 
>      if (layoutSlide == null)
>      {
>          // Ситуация, когда презентация не содержит некоторых типов макетов.
>          // Файл презентации содержит только типы макетов Blank и Custom.
>          // Но макетные слайды с типами Custom имеют разные имена слайдов,
>          // такие как "Title", "Title and Content" и т.д. И их можно использовать
>          // в качестве имён для выбора макетного слайда.
>          // Также можно использовать набор типов заполнителей формы. Например,
>          // Слайд с заголовком должен иметь только заполнитель типа Title и т.д.
>          for (ILayoutSlide titleAndObjectLayoutSlide : (Iterable) layoutSlides)
>          {
>              if ("Title and Object".equals(titleAndObjectLayoutSlide.getName()))
>              {
>                  layoutSlide = titleAndObjectLayoutSlide;
>                  break;
>              }
>          }
>          if (layoutSlide == null)
>          {
>              for (ILayoutSlide titleLayoutSlide : (Iterable) layoutSlides)
>              {
>                  if ("Title".equals(titleLayoutSlide.getName()))
>                  {
>                      layoutSlide = titleLayoutSlide;
>                      break;
>                  }
>              }
>              if (layoutSlide == null)
>              {
>                  layoutSlide = layoutSlides.getByType(SlideLayoutType.Blank);
>                  if (layoutSlide == null)
>                  {
>                      layoutSlide = layoutSlides.add(SlideLayoutType.TitleAndObject, "Title and Object");
>                  }
>              }
>          }
>      }
>      // Добавить пустой слайд с добавленным макетным слайдом
>      presentation.getSlides().insertEmptySlide(0, layoutSlide);
>      // Сохранить презентацию
>      presentation.save("AddLayoutSlides_out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращаемое значение:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public final IMasterNotesSlideManager getMasterNotesSlideManager()
```

Возвращает менеджер мастера заметок. Только для чтения [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Возвращаемое значение:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public final IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Возвращает менеджер мастера раздаточных материалов. Только для чтения [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Возвращаемое значение:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public final IFontsManager getFontsManager()
```

Возвращает менеджер шрифтов. Только для чтения [IFontsManager](../../com.aspose.slides/ifontsmanager).

--------------------

> ```
> The following example shows how to add embedded fonts to PowerPoint Presentation.
>  
>  // Загрузить презентацию
>  Presentation pres = new Presentation("Fonts.pptx");
>  try {
>      // Загрузить исходный шрифт для замены
>      IFontData sourceFont = new FontData("Arial");
>      IFontData[] allFonts = pres.getFontsManager().getFonts();
>      for (IFontData font : allFonts)
>      {
>          boolean fontAlreadyEmbedded = false;
>          IFontData[] embeddedFonts = pres.getFontsManager().getEmbeddedFonts();
>          for (int i = 0; i < embeddedFonts.length; i++)
>          {
>              if (embeddedFonts[i].equals(font))
>              {
>                  fontAlreadyEmbedded = true;
>                  break;
>              }
>          }
>          if (!fontAlreadyEmbedded) {
>              pres.getFontsManager().addEmbeddedFont(font, EmbedFontCharacters.All);
>          }
>      }
>      // Сохранить презентацию
>      pres.save("AddEmbeddedFont_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public final ITextStyle getDefaultTextStyle()
```

Возвращает стиль текста по умолчанию для фигур. Только для чтения [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращаемое значение:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public final ICommentAuthorCollection getCommentAuthors()
```

Возвращает коллекцию авторов комментариев. Только для чтения [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Возвращаемое значение:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public final IDocumentProperties getDocumentProperties()
```

Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа. Только для чтения [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Возвращаемое значение:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public final IImageCollection getImages()
```

Возвращает коллекцию всех изображений в презентации. Только для чтения [IImageCollection](../../com.aspose.slides/iimagecollection).

--------------------

> ```
> The following examples shows how to add image as BLOB in PowerPoint Presentation.
>  
>  // создаёт новую презентацию, в которую будет добавлено изображение.
>  Presentation pres = new Presentation();
>  try
>  {
>      // предположим, что у нас есть большой файл изображения, который мы хотим включить в презентацию
>      FileInputStream fip = new FileInputStream("large_image.jpg");
>      try
>      {
>          // Добавим изображение в презентацию — выбираем поведение KeepLocked, потому что мы
>          // НЕ намерены обращаться к файлу "largeImage.png".
>          IPPImage img = pres.getImages().addImage(fip, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
>          // Сохраняет презентацию. Пока выводится большая презентация, потребление памяти
>          // остаётся низким в течение жизненного цикла объекта pres.
>          pres.save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
>      }
>      finally
>      {
>          fip.close();
>      }
>  }
>  catch (java.io.IOException e) { }
>  finally
>  {
>      pres.dispose();
>  }
>  
>  The following examples add a hyperlink to an image in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      // Добавляет изображение в презентацию
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      // Создаёт рамку-изображение на слайде 1, используя ранее добавленное изображение
>      IPictureFrame pictureFrame = pres.getSlides().get_Item(0).getShapes().addPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
>      pictureFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      pictureFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch (IOException e){ }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public final IAudioCollection getAudios()
```

Возвращает коллекцию всех встроенных аудиофайлов в презентации. Только для чтения [IAudioCollection](../../com.aspose.slides/iaudiocollection).

--------------------

> ```
> The following examples shows how to add a hyperlink to an audio file.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAudio audio = pres.getAudios().addAudio(Files.readAllBytes(Paths.get("audio.mp3")));
>      IAudioFrame audioFrame = pres.getSlides().get_Item(0).getShapes().addAudioFrameEmbedded(10, 10, 100, 100, audio);
>      audioFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      audioFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) {}
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public final IVideoCollection getVideos()
```
Возвращает коллекцию всех встроенных видеофайлов в презентации. Только для чтения [IVideoCollection](../../com.aspose.slides/ivideocollection).

--------------------

> ```
> The following examples shows how to create embedded Video Frame in a PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Get the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Embedd vide inside presentation
>      IVideo vid = pres.getVideos().addVideo(new FileInputStream("Wildlife.mp4"));
>      // Add Video Frame
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 350, vid);
>      // Set video to Video Frame
>      vf.setEmbeddedVideo(vid);
>      // Set Play Mode and Volume of the Video
>      vf.setPlayMode(VideoPlayModePreset.Auto);
>      vf.setVolume(AudioVolumeMode.Loud);
>      // Write the PPTX file to disk
>      pres.save("VideoFrame_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a video passing path to the video file directly into AddVideoFrame method for PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IVideoFrame vf = sld.getShapes().addVideoFrame(50, 150, 300, 150, "video1.avi");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add large file through BLOB to a Presentation.
>  
>  // Creates a new presentation to which the video will be added
>  Presentation pres = new Presentation();
>  try {
>      FileInputStream fileStream = new FileInputStream("veryLargeVideo.avi");
>      try {
>          // Let's add the video to the presentation - we chose the KeepLocked behavior because we do
>          //not intend to access the "veryLargeVideo.avi" file.
>          IVideo video = pres.getVideos().addVideo(fileStream, LoadingStreamBehavior.KeepLocked);
>          pres.getSlides().get_Item(0).getShapes().addVideoFrame(0, 0, 480, 270, video);
>          // Saves the presentation. While a large presentation gets outputted, the memory consumption
>          // stays low through the pres object's lifecycle
>          pres.save("presentationWithLargeVideo.pptx", SaveFormat.Pptx);
>      } finally {
>          if (fileStream != null) fileStream.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to export large file through BLOB from PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  // Locks the source file and does NOT load it into memory
>  loadOptions.getBlobManagementOptions().setPresentationLockingBehavior(PresentationLockingBehavior.KeepLocked);
>  // Creates a Presentation's instance, locks the "hugePresentationWithAudiosAndVideos.pptx" file.
>  Presentation pres = new Presentation("Large  Video File Test1.pptx", loadOptions);
>  try {
>      // Let's save each video to a file. To prevent high memory usage, we need a buffer that will be used
>      // to transfer the data from the presentation's video stream to a stream for a newly created video file.
>      byte[] buffer = new byte[81024];
>      // Iterates through the videos
>      for (int index = 0; index < pres.getVideos().size(); index++) {
>          IVideo video = pres.getVideos().get_Item(index);
>          // Opens the presentation video stream. Please, note that we intentionally avoided accessing properties
>          // like video.BinaryData - because this property returns a byte array containing a full video, which then
>          // causes bytes to be loaded into memory. We use video.GetStream, which will return Stream - and does NOT
>          //  require us to load the whole video into the memory.
>          InputStream presVideoStream = video.getStream();
>          try {
>              FileOutputStream outputFileStream = new FileOutputStream("video{index}.avi");
>              try {
>                  int bytesRead;
>                  while ((bytesRead = presVideoStream.read(buffer, 0, buffer.length)) > 0) {
>                      outputFileStream.write(buffer, 0, bytesRead);
>                  }
>              } finally {
>                  if (outputFileStream != null) outputFileStream.close();
>              }
>          } finally {
>              if (presVideoStream != null) presVideoStream.close();
>          }
>          // Memory consumption will remain low regardless of the size of the video or presentation,
>      }
>      // If necessary, you can apply the same steps for audio files.
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to add a hyperlink to a video in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IVideo video = pres.getVideos().addVideo(Files.readAllBytes(Paths.get("video.avi")));
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 100, 100, video);
>      videoFrame.setHyperlinkClick(new Hyperlink("https://www.aspose.com/"));
>      videoFrame.getHyperlinkClick().setTooltip("More than 70% Fortune 100 companies trust Aspose APIs");
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following examples shows how to create Video Frame with Video from Web Source in a PowerPoint Presentation.
>  
>  public static void run()
>  {
>      Presentation pres = new Presentation();
>      try {
>          addVideoFromYouTube(pres, "Tj75Arhq5ho");
>          pres.save("AddVideoFrameFromWebSource_out.pptx", SaveFormat.Pptx);
>      } catch(IOException e) {
>      } finally {
>          if (pres != null) pres.dispose();
>      }
>  }
>  private static void addVideoFromYouTube(Presentation pres, String videoId) throws IOException
>  {
>      //add videoFrame
>      IVideoFrame videoFrame = pres.getSlides().get_Item(0).getShapes().addVideoFrame(10, 10, 427, 240, "https://www.youtube.com/embed/" + videoId);
>      videoFrame.setPlayMode(VideoPlayModePreset.Auto);
> 
>      //load thumbnail
>      String thumbnailUri = "http://img.youtube.com/vi/" + videoId + "/hqdefault.jpg";
>      URL url = new URL(thumbnailUri);
>      URLConnection connection = url.openConnection();
>      connection.setConnectTimeout(5000);
>      connection.setReadTimeout(10000);
>      InputStream input = connection.getInputStream();
>      ByteArrayOutputStream output = new ByteArrayOutputStream();
>      try
>      {
>          byte[] buffer = new byte[8192];
>          for (int count; (count = input.read(buffer)) > 0; )
>          {
>              output.write(buffer, 0, count);
>          }
>          videoFrame.getPictureFormat().getPicture().setImage(pres.getImages().addImage(output.toByteArray()));
>      } finally {
>          if (input != null) input.close();
>          if (output != null) output.close();
>      }
>  }
>  
>  The following examples shows how to extract Video from slide of PowerPoint Presentation.
>  
>  // Instantiate a Presentation object that represents a presentation file
>  Presentation presentation = new Presentation("Video.pptx");
>  try {
>      for (ISlide slide : presentation.getSlides())
>      {
>          for (IShape shape : presentation.getSlides().get_Item(0).getShapes())
>          {
>              if (shape instanceof VideoFrame)
>              {
>                  IVideoFrame vf = (IVideoFrame) shape;
>                  String type = vf.getEmbeddedVideo().getContentType();
>                  int ss = type.lastIndexOf('/');
>                  type = type.substring(ss + 1);
>                  byte[] buffer = vf.getEmbeddedVideo().getBinaryData();
>                  FileOutputStream fop = new FileOutputStream("NewVideo_out." + type);
>                  try
>                  {
>                      fop.write(buffer);
>                      fop.flush();
>                      fop.close();
>                  }
>                  finally
>                  {
>                      if (presentation != null) presentation.dispose();
>                  }
>              }
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Возвращаемое значение:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getSlideShowSettings() {#getSlideShowSettings--}
```
public final SlideShowSettings getSlideShowSettings()
```

Возвращает настройки показа слайдов для презентации.

**Возвращаемое значение:**
[SlideShowSettings](../../com.aspose.slides/slideshowsettings)
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final IDigitalSignatureCollection getDigitalSignatures()
```

Возвращает коллекцию подписей, используемых для подписи презентации. Только для чтения [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                   + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

Возвращает пользовательские данные презентации. Только для чтения [ICustomData](../../com.aspose.slides/icustomdata).

**Возвращаемое значение:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public final ICustomXmlPart[] getAllCustomXmlParts()
```

Возвращает все пользовательские части данных в презентации. Только для чтения ICustomXmlPart[].

--------------------

> ```
> The following examples show how to clear all custom xml parts from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("PresentationWithCustomXml.pptx");
>  try {
>      // Перебрать все пользовательские XML части
>      for (ICustomXmlPart item : pres.getAllCustomXmlParts())
>      {
>          item.remove();
>      }
>      pres.save("out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
com.aspose.slides.ICustomXmlPart[]
### getVbaProject() {#getVbaProject--}
```
public final IVbaProject getVbaProject()
```

Получает или задает проект VBA с макросами презентации. Чтение/запись [IVbaProject](../../com.aspose.slides/ivbaproject).

**Возвращаемое значение:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public final void setVbaProject(IVbaProject value)
```

Получает или задает проект VBA с макросами презентации. Чтение/запись [IVbaProject](../../com.aspose.slides/ivbaproject).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

Обеспечивает простой доступ ко всем гиперссылкам, содержащимся на всех слайдах презентации (не в мастер-, макетных, слайдах заметок). Только для чтения [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Возвращаемое значение:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public final IViewProperties getViewProperties()
```

Получает свойства просмотра презентации в целом. Только для чтения [IViewProperties](../../com.aspose.slides/iviewproperties).

**Возвращаемое значение:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public final int getFirstSlideNumber()
```

Представляет номер первого слайда в презентации

**Возвращаемое значение:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public final void setFirstSlideNumber(int value)
```

Представляет номер первого слайда в презентации

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabelCollection getSensitivityLabels()
```

Возвращает коллекцию меток чувствительности, примененных к документу презентации. Только для чтения [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Вывести применённые метки
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Добавить новую метку
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Получить Id метки чувствительности из политики
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Получить идентификатор сайта Azure AD из политики
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### getSlideById(long id) {#getSlideById-long-}
```
public final IBaseSlide getSlideById(long id)
```

Возвращает объект Slide, MasterSlide или LayoutSlide по идентификатору.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | long | Идентификатор слайда. |

**Возвращаемое значение:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - объект IBaseSlide.
### getSourceFormat() {#getSourceFormat--}
```
public final int getSourceFormat()
```

Возвращает информацию о том, из какого формата была загружена презентация. Только для чтения [SourceFormat](../../com.aspose.slides/sourceformat).

**Возвращаемое значение:**
int
### getMasterTheme() {#getMasterTheme--}
```
public final IMasterTheme getMasterTheme()
```

Возвращает мастер-тему. Только для чтения [IMasterTheme](../../com.aspose.slides/imastertheme).

--------------------

> ```
> The following examples shows how to change a theme effect by altering parts of elements of PowerPoint Presentation.
>  
>  //Создать объект презентации, представляющий файл презентации
>  Presentation pres = new Presentation("Subtle_Moderate_Intense.pptx");
>  try {
>      pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(0).getFillFormat().getSolidFillColor().setColor(Color.RED);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).setFillType(FillType.Solid);
>      ((FillFormat)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getSolidFillColor().setColor(Color.GREEN);
>      ((EffectStyle)pres.getMasterTheme().getFormatScheme().getLineStyles().get_Item(2)).getEffectFormat().getOuterShadowEffect().setDistance(10f);
>      pres.save("Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public final void save(String fname, int format)
```

Сохраняет все слайды презентации в файл в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| format | int | Формат экспортируемых данных. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```

Сохраняет все слайды презентации в поток в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| format | int | Формат экспортируемых данных. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int format, ISaveOptions options)
```

Сохраняет все слайды презентации в файл в указанном формате с дополнительными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int format, ISaveOptions options)
```

Сохраняет все слайды презентации в поток в указанном формате с дополнительными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public final void save(IXamlOptions options)
```

Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Параметры формата XAML. |

### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public final IImage[] getImages(IRenderingOptions options)
```

Возвращает объекты Image для всех слайдов презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры Tiff. |

**Возвращаемое значение:**
com.aspose.slides.IImage[] - объекты Image.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides)
```

Возвращает объекты Thumbnail Image для указанных слайдов презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры Tiff. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |

**Возвращаемое значение:**
com.aspose.slides.IImage[] - объекты Image.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры Tiff. |
| scaleX | float | Значение, на которое масштабировать этот Thumbnail по оси X. |
| scaleY | float | Значение, на которое масштабировать этот Thumbnail по оси Y. |

**Возвращаемое значение:**
com.aspose.slides.IImage[] - объекты Image.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры Tiff. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |
| scaleX | float | Значение, на которое масштабировать этот Thumbnail по оси X. |
| scaleY | float | Значение, на которое масштабировать этот Thumbnail по оси Y. |

**Возвращаемое значение:**
com.aspose.slides.IImage[] - объекты Image.
### getImages(IRenderingOptions options, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, Dimension imageSize)
```

Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры Tiff. |
| imageSize | java.awt.Dimension | Размер создаваемого изображения. |

**Возвращаемое значение:**
com.aspose.slides.IImage[] - объекты Image.
### getImages(IRenderingOptions options, int[] slides, Dimension imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---java.awt.Dimension-}
```
public final IImage[] getImages(IRenderingOptions options, int[] slides, Dimension imageSize)
```

Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры Tiff. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |
| imageSize | java.awt.Dimension | Размер создаваемого изображения. |

**Возвращаемое значение:**
com.aspose.slides.IImage[] - объекты Image.
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public final void save(String fname, int[] slides, int format)
```

Сохраняет указанные слайды презентации в файл в указанном формате, сохраняет нумерацию страниц.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(String fname, int[] slides, int format, ISaveOptions options)
```

Сохраняет указанные слайды презентации в файл в указанном формате, сохраняет нумерацию страниц.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public final void save(OutputStream stream, int[] slides, int format)
```

Сохраняет указанные слайды презентации в поток в указанном формате, сохраняет нумерацию страниц.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public final void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Сохраняет указанные слайды презентации в поток в указанном формате, сохраняет нумерацию страниц.

--------------------

> ```
> Следующий пример показывает, как преобразовать PowerPoint в PNG.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  Следующий пример показывает, как преобразовать PowerPoint в PNG с пользовательскими размерами.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      float scaleX = 2f;
>      float scaleY = 2f;
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(scaleX, scaleY), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  Следующий пример показывает, как преобразовать PowerPoint в PNG с заданным размером.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Dimension size = new Dimension(960, 720);
>      for (int index = 0; index < pres.getSlides().size(); index++) {
>          ISlide slide = pres.getSlides().get_Item(index);
>          ImageIO.write(slide.getThumbnail(size), "PNG", new java.io.File("slide_" + index + ".png"));
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| slides | int[] | Массив с позициями слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Объединяет порции с одинаковым форматированием во всех абзацах во всех приемлемых фигурах на всех слайдах.

### dispose() {#dispose--}
```
public final void dispose()
```

Освобождает все ресурсы, используемые этим объектом Presentation.

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Возвращает родительскую презентацию текста. Только для чтения [IPresentation](../../com.aspose.slides/ipresentation).

**Возвращаемое значение:**
[IPresentation](../../com.aspose.slides/ipresentation)
### highlightText(String text, Color highlightColor) {#highlightText-java.lang.String-java.awt.Color-}
```
public final void highlightText(String text, Color highlightColor)
```

Выделяет все совпадения образца текста указанным цветом.

> ```
> Следующий пример кода показывает, как выделить текст в презентации PowerPoint.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // выделение всех отдельных вхождений 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для выделения. |
| highlightColor | java.awt.Color | Цвет для выделения текста. |

### highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.awt.Color-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void highlightText(String text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Выделяет все совпадения образца текста указанным цветом.

> ```
> Следующий пример кода показывает, как выделить текст в презентации PowerPoint.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // выделение всех отдельных вхождений 'the'
>      presentation.highlightText("the", Color.MAGENTA, textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | Текст для выделения. |
| highlightColor | java.awt.Color | Цвет для выделения текста. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.awt.Color-com.aspose.slides.IFindResultCallback-}
```
public final void highlightRegex(Pattern regex, Color highlightColor, IFindResultCallback callback)
```

Выделяет все совпадения регулярного выражения указанным цветом.

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // highlighting all words with 10 symbols or longer
>      presentation.highlightRegex(regex, Color.BLUE, null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Регулярное выражение java.util.regex.Pattern для получения строк для выделения. |
| highlightColor | java.awt.Color | Цвет для выделения текста. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback).
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public final void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```


Заменяет все вхождения указанного текста другим указанным текстом.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Заменить все отдельные вхождения 'the' на '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldText | java.lang.String | Строка, которую нужно заменить. |
| newText | java.lang.String | Строка, заменяющая все вхождения oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public final void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```


Заменяет все совпадения регулярного выражения указанной строкой.

--------------------

> ```
> Следующий пример кода показывает, как заменить текст с помощью регулярного выражения указанной строкой.
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      Pattern regex = Pattern.compile("\\b[^\\s]{10,}\\b");
>      // Заменить все слова из 10 и более символов на '***'
>      presentation.replaceRegex(regex, "***", null);
>      presentation.save("SomePresentation-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Регулярное выражение java.util.regex.Pattern, используемое для получения строк для замены. |
| newText | java.lang.String | Строка, заменяющая все вхождения строк, подлежащих замене. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |