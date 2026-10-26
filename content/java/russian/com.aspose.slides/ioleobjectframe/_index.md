---
title: IOleObjectFrame
second_title: Aspose.Slides для Java справочник API
description: Представляет OLE-объект на слайде.
type: docs
url: /ru/com.aspose.slides/ioleobjectframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Представляет OLE-объект на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Возвращает объект свойств заливки изображения OleObject. |
| [getObjectName()](#getObjectName--) | Возвращает или задает имя объекта. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Возвращает или задает имя объекта. |
| [getEmbeddedData()](#getEmbeddedData--) | Получает информацию о внедрённых данных OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Устанавливает информацию о внедрённых данных OLE. |
| [getObjectProgId()](#getObjectProgId--) | Возвращает ProgID объекта. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Возвращает ProgID объекта. |
| [getLinkFileName()](#getLinkFileName--) | Возвращает полный путь к связанному файлу. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает полный путь к связанному файлу. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает полный путь к связанному файлу. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Возвращает имя файла внедрённого OLE-объекта |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Возвращает путь внедрённого OLE-объекта |
| [isObjectIcon()](#isObjectIcon--) | Определяет, отображается ли объект как значок. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Определяет, отображается ли объект как значок. |
| [isObjectLink()](#isObjectLink--) | Определяет, связан ли объект с внешним файлом. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Определяет, обновляется ли связанный внедрённый объект автоматически при открытии или печати презентации. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Определяет, обновляется ли связанный внедрённый объект автоматически при открытии или печати презентации. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Возвращает или задает заголовок значка OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Возвращает или задает заголовок значка OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Возвращает объект свойств заливки изображения OleObject. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращает:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Возвращает или задает имя объекта. Чтение/запись String.

**Возвращает:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Возвращает или задает имя объекта. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Получает информацию о внедрённых данных OLE. Только для чтения [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Возвращает:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Устанавливает информацию о внедрённых данных OLE.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Встроенные данные [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

Этот метод изменяет свойства объекта, чтобы отразить новые данные, и устанавливает флаг IsObjectLink в false, указывая, что OLE-объект внедрён. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Возвращает ProgID объекта. Только для чтения String.

**Возвращает:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

Возвращает ProgID объекта. Только для чтения String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

Возвращает полный путь к связанному файлу. Будет использовано краткое имя файла. Только для чтения String.

**Возвращает:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Возвращает полный путь к связанному файлу. Будет использовано полное имя файла. Чтение/запись String.

**Возвращает:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Возвращает полный путь к связанному файлу. Будет использовано полное имя файла. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
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
public abstract String getEmbeddedFileLabel()
```

Возвращает имя файла внедрённого OLE-объекта

**Возвращает:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Возвращает путь внедрённого OLE-объекта

**Возвращает:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Определяет, отображается ли объект как значок. Чтение/запись boolean.

**Возвращает:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Определяет, отображается ли объект как значок. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Определяет, связан ли объект с внешним файлом. Только для чтения boolean.

**Возвращает:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Определяет, обновляется ли связанный внедрённый объект автоматически при открытии или печати презентации. Чтение/запись boolean.

**Возвращает:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Определяет, обновляется ли связанный внедрённый объект автоматически при открытии или печати презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Возвращает или задает заголовок значка OleObject. Чтение/запись String.

--------------------

Когда IsObjectIcon == false, это значение игнорируется. Строка может быть усечена в соответствии с размером значка OLE.

**Возвращает:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Возвращает или задает заголовок значка OleObject. Чтение/запись String.

--------------------

Когда IsObjectIcon == false, это значение игнорируется. Строка может быть усечена в соответствии с размером значка OLE.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |