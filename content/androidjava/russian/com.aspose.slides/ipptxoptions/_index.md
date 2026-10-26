---
title: IPptxOptions
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет параметры для сохранения презентаций OpenXml форматов PPTX, PPSX, POTX, PPTM, PPSM, POTM.
type: docs
url: /ru/com.aspose.slides/ipptxoptions/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

Представляет параметры для сохранения презентаций OpenXml (PPTX, PPSX, POTX, PPTM, PPSM, POTM).
## Методы

| Метод | Описание |
| --- | --- |
| [getConformance()](#getConformance--) | Указывает класс соответствия, которому соответствует документ Presentation. |
| [setConformance(int value)](#setConformance-int-) | Указывает класс соответствия, которому соответствует документ Presentation. |
| [getZip64Mode()](#getZip64Mode--) | Указывает, используется ли формат ZIP64 для документа Presentation. |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Указывает, используется ли формат ZIP64 для документа Presentation. |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | Указывает, будет ли обновлен миниатюрный образ презентации. |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | Указывает, будет ли обновлен миниатюрный образ презентации. |
| [getCompressionLevel()](#getCompressionLevel--) | Указывает уровень сжатия, используемый при сохранении документа презентации. |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | Указывает уровень сжатия, используемый при сохранении документа презентации. |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```

Указывает класс соответствия, которому соответствует документ Presentation. Значение по умолчанию [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Возвращаемое значение:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```

Указывает класс соответствия, которому соответствует документ Presentation. Значение по умолчанию [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```

Указывает, используется ли формат ZIP64 для документа Presentation. Значение по умолчанию [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public abstract void setZip64Mode(int value)
```

Указывает, используется ли формат ZIP64 для документа Presentation. Значение по умолчанию [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Пример:
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
public abstract boolean getRefreshThumbnail()
```

Указывает, будет ли обновлен миниатюрный образ презентации. Чтение/запись булевого значения. Значение по умолчанию **true**.

--------------------

> ```
> Пример:
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

Когда значение параметра **true**, будет сгенерирован новый миниатюрный образ.

Когда значение параметра **false**, текущий миниатюрный образ будет сохранён без изменений.

**Возвращаемое значение:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```

Указывает, будет ли обновлен миниатюрный образ презентации. Чтение/запись булевого значения. Значение по умолчанию **true**.

--------------------

> ```
> Пример:
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

Когда значение параметра **true**, будет сгенерирован новый миниатюрный образ.

Когда значение параметра **false**, текущий миниатюрный образ будет сохранён без изменений.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```

Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Пример:
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

Более высокие уровни сжатия дают меньший размер файлов, но требуют больше времени обработки. Фактическое соотношение сжатия зависит от содержания презентации.

**Возвращаемое значение:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```

Указывает уровень сжатия, используемый при сохранении документа презентации. Значение по умолчанию [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

--------------------

> ```
> Пример:
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

Более высокие уровни сжатия дают меньший размер файлов, но требуют больше времени обработки. Фактическое соотношение сжатия зависит от содержания презентации.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |