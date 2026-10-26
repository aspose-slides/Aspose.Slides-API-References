---
title: PptxOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет параметры для сохранения презентаций OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
type: docs
url: /ru/com.aspose.slides/pptxoptions/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Все реализованные интерфейсы:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

Представляет параметры для сохранения презентаций OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | Создает новый экземпляр PptxOptions |
## Методы

| Метод | Описание |
| --- | --- |
| [getConformance()](#getConformance--) | Указывает класс соответствия, которому соответствует документ Presentation. |
| [setConformance(int value)](#setConformance-int-) | Указывает класс соответствия, которому соответствует документ Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Указывает, используется ли формат ZIP64 для документа Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Указывает, используется ли формат ZIP64 для документа Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Указывает, будет ли обновлена миниатюра презентации. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Указывает, будет ли обновлена миниатюра презентации. |
| [getCompressionLevel()](#getCompressionLevel--) | Указывает уровень сжатия, используемый при сохранении документа презентации. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Указывает уровень сжатия, используемый при сохранении документа презентации. |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

Создает новый экземпляр PptxOptions

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Указывает класс соответствия, которому соответствует документ Presentation. Значение по умолчанию — [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Возвращаемое значение:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Указывает класс соответствия, которому соответствует документ Presentation. Значение по умолчанию — [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Указывает, используется ли формат ZIP64 для документа Presentation. Значение по умолчанию — [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Возвращаемое значение:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public final void setZip64Mode(int value)
```

Указывает, используется ли формат ZIP64 для документа Presentation. Значение по умолчанию — [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public final boolean getRefreshThumbnail()
```

Указывает, будет ли обновлена миниатюра презентации. Чтение/запись boolean. Значение по умолчанию — **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Когда значение параметра **true**, будет создана новая миниатюра.

Когда значение параметра **false**, текущая миниатюра будет сохранена без изменений.

**Возвращаемое значение:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

Указывает, будет ли обновлена миниатюра презентации. Чтение/запись boolean. Значение по умолчанию — **true**.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Когда значение параметра **true**, будет создана новая миниатюра.

Когда значение параметра **false**, текущая миниатюра будет сохранена без изменений.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию — [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Более высокие уровни сжатия дают более мелкие файлы, но требуют больше времени на обработку. Фактическое соотношение сжатия зависит от содержимого презентации.

**Возвращаемое значение:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию — [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Более высокие уровни сжатия дают более мелкие файлы, но требуют больше времени на обработку. Фактическое соотношение сжатия зависит от содержимого презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |