---
title: ShapeThumbnailBounds
second_title: Referência da API Aspose.Slides para Java
description: Enumeração dos tipos de limites da miniatura de forma.
type: docs
url: /pt/com.aspose.slides/shapethumbnailbounds/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumeração dos tipos de limites da miniatura de forma.
## Campos

| Campo | Descrição |
| --- | --- |
| [Slide](#Slide) | A miniatura da forma terá o tamanho igual ao tamanho do slide. |
| [Shape](#Shape) | A miniatura da forma terá o tamanho igual ao retângulo de limites da forma, levando em conta as configurações de contorno da forma. |
| [Appearance](#Appearance) | A miniatura da forma terá o tamanho igual à aparência da forma (dentro dos limites de um slide). |
### Slide {#Slide}
```
public static final int Slide
```

A miniatura da forma terá o tamanho igual ao tamanho do slide. A posição da forma será salva.

### Shape {#Shape}
```
public static final int Shape
```

A miniatura da forma terá o tamanho igual ao retângulo de limites da forma, levando em conta as configurações de contorno da forma.

### Appearance {#Appearance}
```
public static final int Appearance
```

A miniatura da forma terá o tamanho igual à aparência da forma (dentro dos limites de um slide). Pode haver casos em que a aparência da forma não se ajuste aos limites da forma. Por exemplo, rotação, união em meia-esquadria de ângulo agudo, efeitos 3D, etc.