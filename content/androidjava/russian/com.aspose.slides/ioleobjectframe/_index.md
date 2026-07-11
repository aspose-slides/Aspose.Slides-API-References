---
title: IOleObjectFrame
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет объект OLE на слайде.
type: docs
url: /ru/com.aspose.slides/ioleobjectframe/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Представляет объект OLE на слайде.
## Методы

| Метод | Описание |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Возвращает объект свойств заливки изображения OleObject. |
| [getObjectName()](#getObjectName--) | Возвращает или задает имя объекта. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Возвращает или задает имя объекта. |
| [getEmbeddedData()](#getEmbeddedData--) | Получает информацию о внедренных данных OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Устанавливает информацию о внедренных данных OLE. |
| [getObjectProgId()](#getObjectProgId--) | Возвращает ProgID объекта. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Возвращает ProgID объекта. |
| [getLinkFileName()](#getLinkFileName--) | Возвращает полный путь к связанному файлу. |
| [getLinkPathLong()](#getLinkPathLong--) | Возвращает полный путь к связанному файлу. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Возвращает полный путь к связанному файлу. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Возвращает имя файла внедренного OLE-объекта |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Возвращает путь к внедренному OLE-объекту |
| [isObjectIcon()](#isObjectIcon--) | Определяет, отображается ли объект в виде значка. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Определяет, отображается ли объект в виде значка. |
| [isObjectLink()](#isObjectLink--) | Определяет, связан ли объект с внешним файлом. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Определяет, обновляется ли автоматически связанный внедренный объект при открытии или печати презентации. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Определяет, обновляется ли автоматически связанный внедренный объект при открытии или печати презентации. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Возвращает или задает заголовок для значка OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Возвращает или задает заголовок для значка OleObject. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

Возвращает объект свойств заливки изображения OleObject. Только для чтения [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Возвращаемое значение:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

Возвращает или задает имя объекта. String, чтение/запись.

**Возвращаемое значение:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

Возвращает или задает имя объекта. String, чтение/запись.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

Получает информацию о внедренных данных OLE. Только для чтения [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Возвращаемое значение:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Устанавливает информацию о внедренных данных OLE.

--------------------

> ```
> Следующий пример демонстрирует, как изменить встроенные данные OLE
>  и его тип для существующего объекта [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Внедренные данные [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

This method changes the properties of the object to reflect the new data and sets the IsObjectLink flag to false, indicating that the OLE object is embedded. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

Возвращает ProgID объекта. Только для чтения String.

**Возвращаемое значение:**
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

Возвращает полный путь к связанному файлу. Будет использовано короткое имя файла. String, только для чтения.

**Возвращаемое значение:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

Возвращает полный путь к связанному файлу. Будет использовано полное имя файла. String, чтение/запись.

**Возвращаемое значение:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

Возвращает полный путь к связанному файлу. Будет использовано полное имя файла. String, чтение/запись.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

Возвращает относительный путь к связанному файлу, если он присутствует, иначе возвращает пустую строку. String, только для чтения.

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


В презентациях Ppt некоторые ссылки на объекты Ole могут иметь относительное представление.

**Возвращаемое значение:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

Возвращает имя файла внедренного OLE-объекта

**Возвращаемое значение:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

Возвращает путь к внедренному OLE-объекту

**Возвращаемое значение:**
java.lang.String

### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

Определяет, отображается ли объект в виде значка. boolean, чтение/запись.

**Возвращаемое значение:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

Определяет, отображается ли объект в виде значка. boolean, чтение/запись.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

Определяет, связан ли объект с внешним файлом. boolean, только для чтения.

**Возвращаемое значение:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

Определяет, обновляется ли автоматически связанный внедренный объект при открытии или печати презентации. boolean, чтение/запись.

**Возвращаемое значение:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

Определяет, обновляется ли автоматически связанный внедренный объект при открытии или печати презентации. boolean, чтение/запись.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

Возвращает или задает заголовок для значка OleObject. String, чтение/запись.

--------------------

Когда IsObjectIcon == false, это значение игнорируется. Строка может быть обрезана в соответствии с размером значка OLE.

**Возвращаемое значение:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

Возвращает или задает заголовок для значка OleObject. String, чтение/запись.

--------------------

Когда IsObjectIcon == false, это значение игнорируется. Строка может быть обрезана в соответствии с размером значка OLE.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |