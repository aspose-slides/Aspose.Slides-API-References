---
title: OleObjectFrame
second_title: Справочник API Aspose.Slides для Java
description: Представляет объект OLE на слайде.
type: docs
url: /ru/com.aspose.slides/oleobjectframe/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Все реализованные интерфейсы:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Представляет объект OLE на слайде.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Загружает PPTX в объект презентации
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Получает первый слайд
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Приводит форму к типу OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Читает объект OLE и записывает его на диск
>      if (oleObjectFrame != null) {
>          // Получает данные встроенного файла
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Получает расширение встроенного файла
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Создает путь для сохранения извлечённого файла
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Сохраняет извлечённые данные
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Возвращает объект свойств заполнения изображения OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Возвращает или задает заголовок для иконки OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Возвращает или задает заголовок для иконки OleObject. |
| [getObjectName()](#getObjectName--) | Возвращает или задает имя объекта. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Возвращает или задает имя объекта. |
| [getObjectProgId()](#getObjectProgId--) | Возвращает ProgID объекта. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Возвращает ProgID объекта. |
| [getLinkFileName()](#getLinkFileName--) | Возвращает полный путь к связанному файлу. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает полный путь к связанному файлу. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает полный путь к связанному файлу. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Возвращает имя файла встроенного объекта OLE |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Возвращает путь встроенного объекта OLE |
| [getEmbeddedData()](#getEmbeddedData--) | Получает или задает информацию о встроенных данных OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Задает информацию о встроенных данных OLE. |
| [isObjectIcon()](#isObjectIcon--) | Определяет, отображается ли объект в виде иконки. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Определяет, отображается ли объект в виде иконки. |
| [isObjectLink()](#isObjectLink--) | Определяет, связан ли объект с внешним файлом. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Определяет, обновляется ли связанный встроенный объект автоматически при открытии или печати презентации. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Определяет, обновляется ли связанный встроенный объект автоматически при открытии или печати презентации. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Возвращает объект свойств заполнения изображения OleObject. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращает:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Возвращает или задает заголовок для иконки OleObject. Чтение/запись String.

--------------------

Когда IsObjectIcon == false, это значение игнорируется. Строка может быть усечена в зависимости от размера иконки Ole.

**Возвращает:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Возвращает или задает заголовок для иконки OleObject. Чтение/запись String.

--------------------

Когда IsObjectIcon == false, это значение игнорируется. Строка может быть усечена в зависимости от размера иконки Ole.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Возвращает или задает имя объекта. Чтение/запись String.

**Возвращает:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Возвращает или задает имя объекта. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Возвращает ProgID объекта. Только для чтения String.

**Возвращает:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Возвращает ProgID объекта. Только для чтения String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Возвращает полный путь к связанному файлу. Будет использовано короткое имя файла. Только для чтения String.

**Возвращает:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Возвращает полный путь к связанному файлу. Будет использовано длинное имя файла. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Возвращает полный путь к связанному файлу. Будет использовано длинное имя файла. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. Только для чтения String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

--------------------

В презентациях Ppt некоторые ссылки на объекты Ole могут иметь относительное представление.

**Возвращает:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

Возвращает имя файла встроенного объекта OLE

**Возвращает:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Возвращает путь встроенного объекта OLE

**Возвращает:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Получает или задает информацию о встроенных данных OLE. Чтение/запись [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Возвращает:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Задает информацию о встроенных данных OLE.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Embedded data [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Этот метод изменяет свойства объекта, чтобы отразить новые данные, и устанавливает флаг IsObjectLink в false, указывая, что объект OLE встроен. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Определяет, отображается ли объект в виде иконки. Чтение/запись  boolean .

**Возвращает:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Определяет, отображается ли объект в виде иконки. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Определяет, связан ли объект с внешним файлом. Только для чтения  boolean .

**Возвращает:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Определяет, обновляется ли связанный встроенный объект автоматически при открытии или печати презентации. Чтение/запись  boolean .

**Возвращает:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Определяет, обновляется ли связанный встроенный объект автоматически при открытии или печати презентации. Чтение/запись  boolean .

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |