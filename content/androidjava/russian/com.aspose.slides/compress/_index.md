---
title: Compress
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет группу методов, предназначенных для сжатия .
type: docs
url: /ru/com.aspose.slides/compress/
---
**Наследование:**
java.lang.Object
```
public class Compress
```

Представляет группу методов, предназначенных для сжатия [Presentation](../../com.aspose.slides/presentation).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Compress()](#Compress--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых мастер-слайдов. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых слайдов-макетов. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых символов из встроенных шрифтов. |
### Compress() {#Compress--}
```
public Compress()
```


### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```


Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых мастер-слайдов.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedMasterSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Экземпляр презентации |

### removeUnusedLayoutSlides(Presentation pres) {#removeUnusedLayoutSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedLayoutSlides(Presentation pres)
```


Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых слайдов-макетов.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.removeUnusedLayoutSlides(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Экземпляр презентации |

### compressEmbeddedFonts(Presentation pres) {#compressEmbeddedFonts-com.aspose.slides.Presentation-}
```
public static void compressEmbeddedFonts(Presentation pres)
```


Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых символов из встроенных шрифтов.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressEmbeddedFonts(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| pres | [Presentation](../../com.aspose.slides/presentation) | Экземпляр презентации |