---
title: HandleRepeatedSpaces
second_title: Referencia de API de Java para Aspose.Slides para Android
description: Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.
type: docs
url: /es/com.aspose.slides/handlerepeatedspaces/
---
**Herencia:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class HandleRepeatedSpaces extends System.Enum
```

Especifica cómo se deben manejar los caracteres de espacio regular repetidos durante la exportación a Markdown.
## Campos

| Campo | Descripción |
| --- | --- |
| [None](#None) | Todos los espacios se conservan como caracteres de espacio regular sin ningún cambio. |
| [AlternateSpacesToNbsp](#AlternateSpacesToNbsp) | Convierte secuencias de dos o más espacios regulares consecutivos alternando entre caracteres de espacio regular y entidades de espacio no divisible NBSP. |
| [MultipleSpacesToNbsp](#MultipleSpacesToNbsp) | Convierte secuencias de dos o más espacios regulares consecutivos conservando el primer espacio como carácter de espacio regular y reemplazando todos los espacios posteriores por entidades de espacio no divisible NBSP. |
### None {#None}
```
public static final int None
```

Todos los espacios se conservan como caracteres de espacio regular sin ningún cambio. No se aplica transformación, y los espacios consecutivos múltiples se exportan tal cual.

### AlternateSpacesToNbsp {#AlternateSpacesToNbsp}
```
public static final int AlternateSpacesToNbsp
```

Convierte secuencias de dos o más espacios regulares consecutivos alternando entre caracteres de espacio regular y entidades de espacio no divisible NBSP. El primer espacio siempre se conserva como espacio regular.

### MultipleSpacesToNbsp {#MultipleSpacesToNbsp}
```
public static final int MultipleSpacesToNbsp
```

Convierte secuencias de dos o más espacios regulares consecutivos conservando el primer espacio como carácter de espacio regular y reemplazando todos los espacios posteriores por entidades de espacio no divisible NBSP.