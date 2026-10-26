---
title: IPresentation
second_title: Справочник API Aspose.Slides для Android через Java
description: Документ презентации
type: docs
url: /ru/com.aspose.slides/ipresentation/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Документ презентации
## Методы

| Метод | Описание |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Возвращает или задает дату и время, которые заменят содержимое полей datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Возвращает или задает дату и время, которые заменят содержимое полей datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Возвращает менеджер HeaderFooter презентации. |
| [getProtectionManager()](#getProtectionManager--) | Получает менеджер разрешений для этой презентации. |
| [getSlides()](#getSlides--) | Возвращает список всех слайдов, определённых в презентации. |
| [getSections()](#getSections--) | Возвращает список всех разделов слайдов, определённых в презентации. |
| [getSlideSize()](#getSlideSize--) | Возвращает объект размера слайда. |
| [getNotesSize()](#getNotesSize--) | Возвращает объект размера слайда заметок. |
| [getLayoutSlides()](#getLayoutSlides--) | Возвращает список всех шаблонных слайдов, определённых в презентации. |
| [getMasters()](#getMasters--) | Возвращает список всех мастер-слайдов, определённых в презентации. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Возвращает менеджер заметок мастера. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Возвращает менеджер раздаточных листов мастера. |
| [getFontsManager()](#getFontsManager--) | Возвращает менеджер шрифтов. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Возвращает стиль текста по умолчанию для фигур. |
| [getCommentAuthors()](#getCommentAuthors--) | Возвращает коллекцию авторов комментариев. |
| [getDocumentProperties()](#getDocumentProperties--) | Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа. |
| [getImages()](#getImages--) | Возвращает коллекцию всех изображений в презентации. |
| [getAudios()](#getAudios--) | Возвращает коллекцию всех встроенных аудиофайлов в презентации. |
| [getVideos()](#getVideos--) | Возвращает коллекцию всех встроенных видеофайлов в презентации. |
| [getCustomData()](#getCustomData--) | Возвращает пользовательские данные презентации. |
| [getVbaProject()](#getVbaProject--) | Получает проект VBA с макросами презентации. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Получает проект VBA с макросами презентации. |
| [getSourceFormat()](#getSourceFormat--) | Возвращает информацию о формате, из которого была загружена презентация. |
| [getMasterTheme()](#getMasterTheme--) | Возвращает мастер-тему презентации. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Предоставляет простой доступ ко всем гиперссылкам, содержащимся в слайдах презентации (не в мастере, шаблоне, слайдах заметок). |
| [getViewProperties()](#getViewProperties--) | Получает свойства просмотра, применимые ко всей презентации. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Представляет номер первого слайда в презентации. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Представляет номер первого слайда в презентации. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Возвращает все пользовательские части данных в презентации. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Возвращает коллекцию подписей, использованных для подписи презентации. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Возвращает коллекцию меток чувствительности, применённых к документу презентации. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Сохраняет все слайды презентации в файл в указанном формате. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Сохраняет все слайды презентации в поток в указанном формате. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Сохраняет все слайды презентации в файл в указанном формате и с дополнительными параметрами. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Сохраняет указанные слайды презентации в файл в указанном формате. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Сохраняет указанные слайды презентации в файл в указанном формате. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Сохраняет указанные слайды презентации в поток в указанном формате. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Сохраняет указанные слайды презентации в поток в указанном формате. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Сохраняет все слайды презентации в набор файлов, представляющих разметку XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Возвращает объекты Thumbnail Image для всех слайдов презентации. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Возвращает объекты Thumbnail Image для указанных слайдов презентации. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером. |
| [getSlideById(long id)](#getSlideById-long-) | Возвращает Slide, MasterSlide или LayoutSlide по Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Объединяет части с одинаковым форматированием во всех абзацах всех приемлемых фигур во всех слайдах. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Выделяет все совпадения образца текста указанным цветом. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Выделяет все совпадения образца текста указанным цветом. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Выделяет все совпадения регулярного выражения указанным цветом. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Заменяет все вхождения указанного текста другим указанным текстом. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Заменяет все совпадения регулярного выражения указанной строкой. |

### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Возвращает или задает дату и время, которые заменят содержимое полей datetime. По умолчанию — время создания этого объекта Presentation. **Чтение/запись** java.util.Date.

**Возвращает:**
java.util.Date

### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Возвращает или задает дату и время, которые заменят содержимое полей datetime. По умолчанию — время создания этого объекта Presentation. **Чтение/запись** java.util.Date.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Date |  |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Возвращает менеджер HeaderFooter презентации. **Только для чтения** [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Возвращает:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)

### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Получает менеджер разрешений для этой презентации. **Только для чтения** [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Возвращает:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)

### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Возвращает список всех слайдов, определённых в презентации. **Только для чтения** [ISlideCollection](../../com.aspose.slides/islidecollection).

**Возвращает:**
[ISlideCollection](../../com.aspose.slides/islidecollection)

### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Возвращает список всех разделов слайдов, определённых в презентации. **Только для чтения** [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Возвращает:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)

### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Возвращает объект размера слайда. **Только для чтения** [ISlideSize](../../com.aspose.slides/islidesize).

**Возвращает:**
[ISlideSize](../../com.aspose.slides/islidesize)

### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Возвращает объект размера слайда заметок. **Только для чтения** [INotesSize](../../com.aspose.slides/inotessize).

**Возвращает:**
[INotesSize](../../com.aspose.slides/inotessize)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Возвращает список всех шаблонных слайдов, определённых в презентации. **Только для чтения** [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Вы можете получить альтернативный API для добавления/вставки/удаления/клонирования шаблонных слайдов, используя свойство IMasterSlide.LayoutSlides.

**Возвращает:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)

### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Возвращает список всех мастер-слайдов, определённых в презентации. **Только для чтения** [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Возвращает:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)

### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Возвращает менеджер заметок мастера. **Только для чтения** [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Возвращает:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)

### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Возвращает менеджер раздаточных листов мастера. **Только для чтения** [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Возвращает:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)

### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Возвращает менеджер шрифтов. **Только для чтения** [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Возвращает:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)

### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Возвращает стиль текста по умолчанию для фигур. **Только для чтения** [ITextStyle](../../com.aspose.slides/itextstyle).

**Возвращает:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Возвращает коллекцию авторов комментариев. **Только для чтения** [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Возвращает:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)

### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Возвращает объект DocumentProperties, содержащий стандартные и пользовательские свойства документа. **Только для чтения** [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Возвращает:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)

### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Возвращает коллекцию всех изображений в презентации. **Только для чтения** [IImageCollection](../../com.aspose.slides/iimagecollection).

**Возвращает:**
[IImageCollection](../../com.aspose.slides/iimagecollection)

### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Возвращает коллекцию всех встроенных аудиофайлов в презентации. **Только для чтения** [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Возвращает:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)

### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Возвращает коллекцию всех встроенных видеофайлов в презентации. **Только для чтения** [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Возвращает:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Возвращает пользовательские данные презентации. **Только для чтения** [ICustomData](../../com.aspose.slides/icustomdata).

**Возвращает:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Получает проект VBA с макросами презентации. **Чтение/запись** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Возвращает:**
[IVbaProject](../../com.aspose.slides/ivbaproject)

### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Получает проект VBA с макросами презентации. **Чтение/запись** [IVbaProject](../../com.aspose.slides/ivbaproject).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |

### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Возвращает информацию о формате, из которого была загружена презентация. **Только для чтения** [SourceFormat](../../com.aspose.slides/sourceformat).

**Возвращает:**
int

### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Возвращает мастер-тему презентации. **Только для чтения** [IMasterTheme](../../com.aspose.slides/imastertheme).

**Возвращает:**
[IMasterTheme](../../com.aspose.slides/imastertheme)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Предоставляет простой доступ ко всем гиперссылкам, содержащимся в слайдах презентации (не в мастере, шаблонах, слайдах заметок). **Только для чтения** [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Возвращает:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Получает свойства просмотра, применимые ко всей презентации. **Только для чтения** [IViewProperties](../../com.aspose.slides/iviewproperties).

**Возвращает:**
[IViewProperties](../../com.aspose.slides/iviewproperties)

### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Представляет номер первого слайда в презентации. **Чтение/запись** int.

**Возвращает:**
int

### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```
public abstract void setFirstSlideNumber(int value)
```

Представляет номер первого слайда в презентации. **Чтение/запись** int.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Возвращает все пользовательские части данных в презентации. **Только для чтения** ICustomXmlPart[].

**Возвращает:**
com.aspose.slides.ICustomXmlPart[]

### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Возвращает коллекцию подписей, использованных для подписи презентации. **Только для чтения** [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

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
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
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


**Возвращает:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Возвращает коллекцию меток чувствительности, применённых к документу презентации. **Только для чтения** [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

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
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Получить идентификатор метки чувствительности из политики
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Получить идентификатор сайта Azure AD из политики
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращает:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)

### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Сохраняет все слайды презентации в файл в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| format | int | Формат экспортируемых данных. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Сохраняет все слайды презентации в поток в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| format | int | Формат экспортируемых данных. |

### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Сохраняет все слайды презентации в файл в указанном формате и с дополнительными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Сохраняет все слайды презентации в поток в указанном формате и с дополнительными параметрами.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Сохраняет указанные слайды презентации в файл в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |

### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Сохраняет указанные слайды презентации в файл в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| fname | java.lang.String | Путь к создаваемому файлу. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Сохраняет указанные слайды презентации в поток в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |

### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Сохраняет указанные слайды презентации в поток в указанном формате.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.OutputStream | Выходной поток. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |
| format | int | Формат экспортируемых данных. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Дополнительные параметры формата. |

### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
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
public abstract IImage[] getImages(IRenderingOptions options)
```

Возвращает объекты Thumbnail Image для всех слайдов презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |

**Возвращает:**
com.aspose.slides.IImage[] - объекты IImage.

### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Возвращает объекты Thumbnail IImage для указанных слайдов презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |

**Возвращает:**
com.aspose.slides.IImage[] - объекты IImage.

### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Возвращает объекты Thumbnail Image для всех слайдов презентации с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| scaleX | float | Значение масштаба по оси X. |
| scaleY | float | Значение масштаба по оси Y. |

**Возвращает:**
com.aspose.slides.IImage[] - объекты Bitmap.

### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Возвращает объекты Thumbnail Image для указанных слайдов презентации с пользовательским масштабированием.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |
| scaleX | float | Значение масштаба по оси X. |
| scaleY | float | Значение масштаба по оси Y. |

**Возвращает:**
com.aspose.slides.IImage[] - объекты IImage.

### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Возвращает объекты Thumbnail Image для всех слайдов презентации с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Размер изображения для создания. |

**Возвращает:**
com.aspose.slides.IImage[] - объекты IImage.

### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Возвращает объекты Thumbnail Image для указанных слайдов презентации с указанным размером.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Параметры рендеринга. |
| slides | int[] | Массив позиций слайдов, начиная с 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Размер изображения для создания. |

**Возвращает:**
com.aspose.slides.IImage[] - объекты IImage.

### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Возвращает Slide, MasterSlide или LayoutSlide по Id.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| id | long | Id слайда. |

**Возвращает:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - объект IBaseSlide.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Объединяет части с одинаковым форматированием во всех абзацах всех приемлемых фигур во всех слайдах.

### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Выделяет все совпадения образца текста указанным цветом.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
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
| highlightColor | java.lang.Integer | Цвет для выделения текста. |

### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Выделяет все совпадения образца текста указанным цветом.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
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
| highlightColor | java.lang.Integer | Цвет для выделения текста. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Выделяет все совпадения регулярного выражения указанным цветом.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
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
| regex | java.util.regex.Pattern | Регулярное выражение для получения строк для выделения. |
| highlightColor | java.lang.Integer | Цвет для выделения текста. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
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
| oldText | java.lang.String | Строка для замены. |
| newText | java.lang.String | Строка, которой заменяются все вхождения oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Параметры поиска текста [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |

### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Заменяет все совпадения регулярного выражения указанной строкой.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
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
| regex | java.util.regex.Pattern | Регулярное выражение для получения строк для замены. |
| newText | java.lang.String | Строка, которой заменяются все вхождения строк для замены. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |