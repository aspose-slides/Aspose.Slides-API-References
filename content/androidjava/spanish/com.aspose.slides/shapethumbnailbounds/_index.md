---
title: ShapeThumbnailBounds
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Enumeración de tipos de límites de miniatura de forma.
type: docs
url: /es/com.aspose.slides/shapethumbnailbounds/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumeración de tipos de límites de miniatura de forma.
## Campos

| Campo | Descripción |
| --- | --- |
| [Slide](#Slide) | La miniatura de la forma tendrá el tamaño igual al de la diapositiva. |
| [Shape](#Shape) | La miniatura de la forma tendrá el tamaño igual al rectángulo de los límites de la forma, teniendo en cuenta la configuración del contorno de la forma. |
| [Appearance](#Appearance) | La miniatura de la forma tendrá el tamaño igual a la apariencia de la forma (dentro de los límites de una diapositiva). |
### Diapositiva {#Slide}
```
public static final int Slide
```

La miniatura de la forma tendrá el tamaño igual al de la diapositiva. La posición de la forma se guardará.

### Forma {#Shape}
```
public static final int Shape
```

La miniatura de la forma tendrá el tamaño igual al rectángulo de los límites de la forma, teniendo en cuenta la configuración del contorno de la forma.

### Apariencia {#Appearance}
```
public static final int Appearance
```

La miniatura de la forma tendrá el tamaño igual a la apariencia de la forma (dentro de los límites de una diapositiva). Puede haber casos en los que la apariencia de la forma no quepa dentro de los límites de la forma. Por ejemplo, rotación, unión inglete de ángulo agudo, efectos 3D, etc.