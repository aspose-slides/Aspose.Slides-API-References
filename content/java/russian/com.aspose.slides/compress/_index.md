---
title: Compress
second_title: Справочник API Aspose.Slides для Java
description: Представляет группу методов, предназначенных для сжатия.
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
| [compressPresentation(Presentation presentation)](#compressPresentation-com.aspose.slides.Presentation-) | Уменьшает размер презентации, применяя все доступные шаги сжатия:

 *  Удаляет неиспользуемые слайды шаблона \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Удаляет неиспользуемые слайды макета \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Оставляет только глифы, реально используемые во встроенных шрифтах \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Снижает разрешение изображений до 150 DPI и удаляет обрезанные области изображений \#compressImages(IPresentation,int).compressImages(IPresentation,int). |
| [removeUnusedMasterSlides(Presentation pres)](#removeUnusedMasterSlides-com.aspose.slides.Presentation-) | Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых слайдов шаблона. |
| [removeUnusedLayoutSlides(Presentation pres)](#removeUnusedLayoutSlides-com.aspose.slides.Presentation-) | Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых слайдов макета. |
| [compressEmbeddedFonts(Presentation pres)](#compressEmbeddedFonts-com.aspose.slides.Presentation-) | Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых символов из встроенных шрифтов. |
| [compressImages(IPresentation presentation, int resolution)](#compressImages-com.aspose.slides.IPresentation-int-) | Снижает разрешение изображений в презентации и удаляет их обрезанные области, аналогично функции PowerPoint «Сжать изображения», примененной ко всем изображениям. |
### Compress() {#Compress--}
```
public Compress()
```


### compressPresentation(Presentation presentation) {#compressPresentation-com.aspose.slides.Presentation-}
```
public static void compressPresentation(Presentation presentation)
```


Уменьшает размер презентации, применяя все доступные шаги сжатия:

 *  Удаляет неиспользуемые слайды шаблона \#removeUnusedMasterSlides(Presentation).removeUnusedMasterSlides(Presentation).
 *  Удаляет неиспользуемые слайды макета \#removeUnusedLayoutSlides(Presentation).removeUnusedLayoutSlides(Presentation).
 *  Оставляет только глифы, реально используемые во встроенных шрифтах \#compressEmbeddedFonts(Presentation).compressEmbeddedFonts(Presentation).
 *  Снижает разрешение изображений до 150 DPI и удаляет обрезанные области изображений \#compressImages(IPresentation,int).compressImages(IPresentation,int).

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressPresentation(pres);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [Presentation](../../com.aspose.slides/presentation) | Презентация для сжатия. |

Чтобы настроить сжатие, например использовать другое разрешение изображений или пропустить шаг, вызывайте перечисленные выше методы по отдельности вместо этого. Обрезанные области изображений удаляются постоянно и не могут быть восстановлены в PowerPoint. |

### removeUnusedMasterSlides(Presentation pres) {#removeUnusedMasterSlides-com.aspose.slides.Presentation-}
```
public static void removeUnusedMasterSlides(Presentation pres)
```

Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых слайдов шаблона.

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

Выполняет сжатие [Presentation](../../com.aspose.slides/presentation) путем удаления неиспользуемых слайдов макета.

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

### compressImages(IPresentation presentation, int resolution) {#compressImages-com.aspose.slides.IPresentation-int-}
```
public static void compressImages(IPresentation presentation, int resolution)
```

Снижает разрешение изображений в презентации и удаляет их обрезанные области, аналогично функции PowerPoint «Сжать изображения», примененной ко всем изображениям. Обрабатываются изображения на слайдах, слайдах макета и слайдах шаблона, включая изображения внутри групповых фигур и заливки изображениями фигур.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      Compress.compressImages(pres, PicturesCompression.Dpi150);
> 
>      pres.save("pres-out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) | Презентация для обработки. |
| resolution | int | Целевая разрешающая способность относительно размера, в котором отображается каждое изображение. [PicturesCompression.DocumentResolution](../../com.aspose.slides/picturescompression\#DocumentResolution) оставляет изображения без изменений. |

Изображения, уже имеющие целевое разрешение или ниже его, оставляются без изменений; изображения никогда не увеличиваются.

Не обрабатываются: фоны слайдов, заливки ячеек таблиц, диаграммы, SmartArt, GIF-изображения (для сохранения анимации), SVG и метафайлы (EMF/WMF).

Обрезанные области удаляются постоянно и не могут быть восстановлены в PowerPoint. |