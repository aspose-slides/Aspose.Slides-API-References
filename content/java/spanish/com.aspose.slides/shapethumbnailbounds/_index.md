---
title: ShapeThumbnailBounds
second_title: Referencia de API de Aspose.Slides for Java
description: Enumeración de tipos de límites de miniaturas de shape.
type: docs
url: /es/com.aspose.slides/shapethumbnailbounds/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumeración de tipos de límites de miniaturas de shape.
## Campos

| Field | Description |
| --- | --- |
| [Slide](#Slide) | Shape thumbnail tendrá el tamaño igual al tamaño de la diapositiva. |
| [Shape](#Shape) | Shape thumbnail tendrá el tamaño igual al rectángulo de límites de shape teniendo en cuenta la configuración del contorno de shape. |
| [Appearance](#Appearance) | Shape thumbnail tendrá el tamaño igual a la apariencia de shape (dentro de los límites de una diapositiva). |
### Slide {#Slide}
```
public static final int Slide
```


Shape thumbnail tendrá el tamaño igual al tamaño de la diapositiva. Shape position será guardada.

### Shape {#Shape}
```
public static final int Shape
```


Shape thumbnail tendrá el tamaño igual al rectángulo de límites de shape teniendo en cuenta la configuración del contorno de shape.

### Appearance {#Appearance}
```
public static final int Appearance
```


Shape thumbnail tendrá el tamaño igual a la apariencia de shape (dentro de los límites de una diapositiva). Puede haber casos en los que la apariencia de shape no encaje en los límites de shape. Por ejemplo, rotación, unión en inglete de ángulo agudo, efectos 3D, etc.