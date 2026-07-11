---
title: LoadOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Позволяет задавать дополнительные параметры, такие как формат или шрифт по умолчанию, при загрузке презентации.
type: docs
url: /ru/com.aspose.slides/loadoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Позволяет указать дополнительные параметры (например, формат или шрифт по умолчанию) при загрузке презентации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Создает новые параметры загрузки по умолчанию. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Создает новые параметры загрузки. |
## Методы

| Метод | Описание |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Возвращает или задает формат презентации для загрузки. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Возвращает или задает формат презентации для загрузки. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Возвращает или задает обычный шрифт, используемый, если исходный шрифт не найден. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Возвращает или задает обычный шрифт, используемый, если исходный шрифт не найден. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Возвращает или задает символный шрифт, используемый, если исходный шрифт не найден. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Возвращает или задает символный шрифт, используемый, если исходный шрифт не найден. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Возвращает или задает азиатский шрифт, используемый, если исходный шрифт не найден. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Возвращает или задает азиатский шрифт, используемый, если исходный шрифт не найден. |
| [getPassword()](#getPassword--) | Получает или задает пароль. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Получает или задает пароль. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Это свойство имеет смысл, если файл презентации защищен паролем. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Это свойство имеет смысл, если файл презентации защищен паролем. |
| [getWarningCallback()](#getWarningCallback--) | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Представляет параметры, которые могут использоваться для управления поведением работы с Binary Large Objects (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Представляет параметры, которые могут использоваться для управления поведением работы с Binary Large Objects (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Указывает источники внешних шрифтов, используемых в презентации. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Указывает источники внешних шрифтов, используемых в презентации. |
| [getInterruptionToken()](#getInterruptionToken--) | Токен для мониторинга запросов прерывания. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Токен для мониторинга запросов прерывания. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Получает параметры для электронных таблиц. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Получает параметры для электронных таблиц. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Возвращает или задает язык по умолчанию для текста презентации. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Возвращает или задает язык по умолчанию для текста презентации. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Определяет, будет ли Aspose.Slides удалять все вложенные бинарные объекты при загрузке презентации. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Определяет, будет ли Aspose.Slides удалять все вложенные бинарные объекты при загрузке презентации. |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Создает новые параметры загрузки по умолчанию.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Создает новые параметры загрузки.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| loadFormat | int | Формат презентации для загрузки. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Возвращает или задает формат презентации для загрузки. Чтение/запись [LoadFormat](../../com.aspose.slides/loadformat).

**Возвращаемое значение:**
int
### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Возвращает или задает формат презентации для загрузки. Чтение/запись [LoadFormat](../../com.aspose.slides/loadformat).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Возвращает или задает обычный шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Используйте параметры загрузки, чтобы задать обычные и азиатские шрифты по умолчанию
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Загрузить презентацию
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Сгенерировать миниатюру слайда
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Сгенерировать PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Сгенерировать XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Возвращает или задает обычный шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Используйте параметры загрузки, чтобы задать обычные и азиатские шрифты по умолчанию
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Загрузить презентацию
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Сгенерировать миниатюру слайда
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Сгенерировать PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Сгенерировать XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Возвращает или задает символный шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Возвращает или задает символный шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Возвращает или задает азиатский шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Возвращает или задает азиатский шрифт, используемый, если исходный шрифт не найден. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Получает или задает пароль. Чтение/запись String.

--------------------

> ```
> Следующий пример кода показывает, как открыть защищённую паролем презентацию PowerPoint.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // работа с расшифрованной презентацией
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Значение: Пароль.

**Возвращаемое значение:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Получает или задает пароль. Чтение/запись String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // работа с расшифрованной презентацией
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Значение: Пароль.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Это свойство имеет смысл, если файл презентации защищен паролем. Значение true означает, что из зашифрованного файла презентации будут загружены только свойства документа, а пароль будет игнорироваться. Значение false означает, что будет загружена вся зашифрованная презентация с использованием правильного пароля. Если презентация не зашифрована, значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не публичны и значение свойства равно true, свойства документа не могут быть загружены, будет выброшено исключение. Чтение/запись boolean.

**Возвращаемое значение:**
boolean
### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Это свойство имеет смысл, если файл презентации защищен паролем. Значение true означает, что из зашифрованного файла презентации будут загружены только свойства документа, а пароль будет игнорироваться. Значение false означает, что будет загружена вся зашифрованная презентация с использованием правильного пароля. Если презентация не зашифрована, значение свойства всегда игнорируется. Если свойства документа зашифрованного файла не публичны и значение свойства равно true, свойства документа не могут быть загружены, будет выброшено исключение. Чтение/запись boolean.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. Чтение/запись [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Возвращаемое значение:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Возвращает или задает объект, получающий предупреждения и решающий, будет ли процесс загрузки продолжен или прерван. Чтение/запись [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Представляет параметры, которые могут использоваться для управления поведением работы с Binary Large Objects (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. Эти параметры предназначены для настройки оптимального соотношения производительности и потребления памяти для конкретной среды или требований.

--------------------

Binary Large Object (BLOB) — бинарные данные, хранящиеся как единый объект; например, BLOB может быть аудио, видео или самой презентацией.

**Возвращаемое значение:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)
### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Представляет параметры, которые могут использоваться для управления поведением работы с Binary Large Objects (BLOB), например, использованием временных файлов или максимальным объёмом BLOB в памяти. Эти параметры предназначены для настройки оптимального соотношения производительности и потребления памяти для конкретной среды или требований.

--------------------

Binary Large Object (BLOB) — бинарные данные, хранящиеся как единый объект; например, BLOB может быть аудио, видео или самой презентацией.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Указывает источники внешних шрифтов, используемых в презентации. Эти шрифты доступны презентации на протяжении её жизненного цикла и не совместно используются другими презентациями.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // работа с презентацией
>  // CustomFont1, CustomFont2, а также шрифты из папок assets\fonts и global\fonts и их подпапок доступны презентации
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Возвращаемое значение:**
[IFontSources](../../com.aspose.slides/ifontsources)
### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Указывает источники внешних шрифтов, используемых в презентации. Эти шрифты доступны презентации на протяжении её жизненного цикла и не совместно используются другими презентациями.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  // работа с презентацией
>  // CustomFont1, CustomFont2, а также шрифты из папок assets\fonts и global\fonts и их подпапок доступны презентации
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Токен для мониторинга запросов прерывания.

--------------------

Этот токен управляет всей жизненной циклом экземпляра [IPresentation](../../com.aspose.slides/ipresentation). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана вызовом метода [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) класса [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Возвращаемое значение:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)
### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Токен для мониторинга запросов прерывания.

--------------------

Этот токен управляет всей жизненной циклом экземпляра [IPresentation](../../com.aspose.slides/ipresentation). Любая длительная операция, такая как загрузка или сохранение презентации, будет прервана вызовом метода [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) класса [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. Чтение/запись [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Возвращаемое значение:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)
### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Возвращает или задает интерфейс обратного вызова, который управляет загрузкой внешних ресурсов. Чтение/запись [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Получает параметры для электронных таблиц. Например, эти параметры влияют на вычисление формул для диаграмм.

**Возвращаемое значение:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Получает параметры для электронных таблиц. Например, эти параметры влияют на вычисление формул для диаграмм.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
```

Возвращает или задает язык по умолчанию для текста презентации. Чтение/запись String.

--------------------

> ```
> Пример:
>   
>  // Используйте параметры загрузки, чтобы задать культуру текста по умолчанию
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Добавьте новую прямоугольную форму с текстом
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Проверить язык первой части
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Возвращаемое значение:**
java.lang.String
### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public final void setDefaultTextLanguage(String value)
```

Возвращает или задает язык по умолчанию для текста презентации. Чтение/запись String.

--------------------

> ```
> Пример:
>   
>  // Используйте параметры загрузки, чтобы задать культуру текста по умолчанию
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Добавьте новую прямоугольную форму с текстом
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Проверьте язык первой части
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Определяет, будет ли Aspose.Slides удалять все вложенные бинарные объекты при загрузке презентации.

Типы вложенных бинарных объектов:

Чтение/запись boolean.

--------------------

> ```
> Следующий пример показывает, как загрузить презентацию без каких-либо вложенных бинарных объектов.
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

**Возвращаемое значение:**
boolean
### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Определяет, будет ли Aspose.Slides удалять все вложенные бинарные объекты при загрузке презентации.

Типы вложенных бинарных объектов:

Чтение/запись boolean.

--------------------

> ```
> Следующий пример показывает, как загрузить презентацию без каких-либо вложенных бинарных объектов.
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