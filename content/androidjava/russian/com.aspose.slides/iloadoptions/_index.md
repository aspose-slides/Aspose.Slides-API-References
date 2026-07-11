---
title: ILoadOptions
second_title: Aspose.Slides для Android через Java API Reference
description: Позволяет указывать дополнительные параметры, такие как формат или шрифт по умолчанию, при загрузке презентации.
type: docs
url: /ru/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Позволяет указывать дополнительные параметры (например, формат или шрифт по умолчанию) при загрузке презентации.
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Возвращает или задаёт формат презентации для загрузки. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Возвращает или задаёт формат презентации для загрузки. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Возвращает или задаёт обычный шрифт, используемый, если исходный шрифт не найден. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Возвращает или задаёт обычный шрифт, используемый, если исходный шрифт не найден. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Возвращает или задаёт шрифт Symbol, используемый, если исходный шрифт не найден. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Возвращает или задаёт шрифт Symbol, используемый, если исходный шрифт не найден. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Возвращает или задаёт азиатский шрифт, используемый, если исходный шрифт не найден. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Возвращает или задаёт азиатский шрифт, используемый, если исходный шрифт не найден. |
| [getPassword()](#getPassword--) | Получает или задаёт пароль. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Получает или задаёт пароль. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Это свойство имеет смысл, если файл презентации защищён паролем. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Это свойство имеет смысл, если файл презентации защищён паролем. |
| [getWarningCallback()](#getWarningCallback--) | Возвращает или задаёт объект, получающий предупреждения и определяющий, продолжать ли процесс загрузки или прервать его. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Возвращает или задаёт объект, получающий предупреждения и определяющий, продолжать ли процесс загрузки или прервать его. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Представляет параметры, которые могут использоваться для управления поведением обработки больших двоичных объектов (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Представляет параметры, которые могут использоваться для управления поведением обработки больших двоичных объектов (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Указывает источники внешних шрифтов, используемых в презентации. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Указывает источники внешних шрифтов, используемых в презентации. |
| [getInterruptionToken()](#getInterruptionToken--) | Токен для отслеживания запросов на прерывание. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Токен для отслеживания запросов на прерывание. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Возвращает или задаёт интерфейс обратного вызова, управляющий загрузкой внешних ресурсов. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Возвращает или задаёт интерфейс обратного вызова, управляющий загрузкой внешних ресурсов. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Возвращает или задаёт язык по умолчанию для текста презентации. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Возвращает или задаёт язык по умолчанию для текста презентации. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации. |
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


Возвращает или задаёт формат презентации для загрузки. Чтение/запись [LoadFormat](../../com.aspose.slides/loadformat).

**Возвращает:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```


Возвращает или задаёт формат презентации для загрузки. Чтение/запись [LoadFormat](../../com.aspose.slides/loadformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```


Возвращает или задаёт обычный шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Возвращает:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```


Возвращает или задаёт обычный шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```


Возвращает или задаёт шрифт Symbol, используемый, если исходный шрифт не найден. Чтение/запись String.

**Возвращает:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```


Возвращает или задаёт шрифт Symbol, используемый, если исходный шрифт не найден. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```


Возвращает или задаёт азиатский шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Возвращает:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```


Возвращает или задаёт азиатский шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```


Получает или задаёт пароль. Чтение/запись String.

Значение: Пароль.

**Возвращает:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```


Получает или задаёт пароль. Чтение/запись String.

Значение: Пароль.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```


Это свойство имеет смысл, если файл презентации защищён паролем. Значение true означает, что из зашифрованного файла презентации должны быть загружены только свойства документа, а пароль игнорируется. Значение false означает, что должна быть загружена вся зашифрованная презентация с использованием правильного пароля. Если презентация не зашифрована, значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не публичны и значение свойства равно true, свойства документа загрузить нельзя, будет выброшено исключение. Чтение/запись boolean.

**Возвращает:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```


Это свойство имеет смысл, если файл презентации защищён паролем. Значение true означает, что из зашифрованного файла презентации должны быть загружены только свойства документа, а пароль игнорируется. Значение false означает, что должна быть загружена вся зашифрованная презентация с использованием правильного пароля. Если презентация не зашифрована, значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не публичны и значение свойства равно true, свойства документа загрузить нельзя, будет выброшено исключение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```


Возвращает или задаёт объект, получающий предупреждения и определяющий, продолжать ли процесс загрузки или прервать его. Чтение/запись [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Возвращает:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```


Возвращает или задаёт объект, получающий предупреждения и определяющий, продолжать ли процесс загрузки или прервать его. Чтение/запись [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```


Представляет параметры, которые могут использоваться для управления поведением обработки больших двоичных объектов (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. Эти параметры предназначены для настройки лучшего соотношения производительности и потребления памяти для конкретной среды или требований.

--------------------

Большой двоичный объект (BLOB) — это двоичные данные, хранящиеся как единый объект; BLOB может быть аудио, видео или самой презентацией.

**Возвращает:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```


Представляет параметры, которые могут использоваться для управления поведением обработки больших двоичных объектов (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. Эти параметры предназначены для настройки лучшего соотношения производительности и потребления памяти для конкретной среды или требований.

--------------------

Большой двоичный объект (BLOB) — это двоичные данные, хранящиеся как единый объект; BLOB может быть аудио, видео или самой презентацией.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```


Указывает источники внешних шрифтов, используемых в презентации. Эти шрифты доступны презентации в течение всего её жизненного цикла и не совместно используются другими презентациями.

**Возвращает:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```


Указывает источники внешних шрифтов, используемых в презентации. Эти шрифты доступны презентации в течение всего её жизненного цикла и не совместно используются другими презентациями.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```


Токен для отслеживания запросов на прерывание.

--------------------

Этот токен управляет всей жизнью экземпляра [IPresentation](../../com.aspose.slides/ipresentation). Любая длительная операция, например загрузка или сохранение презентации, будет прервана вызовом метода [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) объекта [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Возвращает:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```


Токен для отслеживания запросов на прерывание.

--------------------

Этот токен управляет всей жизнью экземпляра [IPresentation](../../com.aspose.slides/ipresentation). Любая длительная операция, например загрузка или сохранение презентации, будет прервана вызовом метода [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) объекта [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```


Возвращает или задаёт интерфейс обратного вызова, управляющий загрузкой внешних ресурсов. Чтение/запись [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Возвращает:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```


Возвращает или задаёт интерфейс обратного вызова, управляющий загрузкой внешних ресурсов. Чтение/запись [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```


Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.

**Возвращает:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```


Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```


Возвращает или задаёт язык по умолчанию для текста презентации. Чтение/запись String.

--------------------

> ```
> Example:
>   
>  // Используйте параметры загрузки, чтобы задать культуру текста по умолчанию
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Добавить новую прямоугольную форму с текстом
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Проверить язык первой части текста
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращает:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```


Возвращает или задаёт язык по умолчанию для текста презентации. Чтение/запись String.

--------------------

> ```
> Example:
>   
>  // Используйте параметры загрузки, чтобы задать культуру текста по умолчанию
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Добавить новую прямоугольную форму с текстом
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Проверить язык первой части текста
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```


Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации.

Типы встроенных двоичных объектов:

 *  
 *  
 *  

Чтение/запись boolean.

--------------------

> ```
> Следующий пример демонстрирует, как загрузить презентацию без каких-либо встроенных двоичных объектов.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

По умолчанию **false**.

**Возвращает:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```


Определяет, будет ли Aspose.Slides удалять все встроенные двоичные объекты при загрузке презентации.

Типы встроенных двоичных объектов:

 *  
 *  
 *  

Чтение/запись boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

По умолчанию **false**.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |