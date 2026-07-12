---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa al gestor que mantiene el comportamiento de todos los marcadores de posición de pie de página, fecha y hora y número de diapositiva de la presentación.
type: docs
url: /es/com.aspose.slides/ipresentationheaderfootermanager/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Representa el gestor que contiene el comportamiento de todos los marcadores de posición de pie de página, fecha y hora y número de diapositiva de la presentación.
## Métodos

| Método | Descripción |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Cambia la visibilidad de todos los marcadores de posición de encabezado, incluidos el maestro de notas, las diapositivas de notas y el maestro de folletos. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Cambia la visibilidad de todos los marcadores de posición de pie de página, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Cambia la visibilidad de todos los marcadores de posición de número de diapositiva, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Cambia la visibilidad de todos los marcadores de posición de fecha y hora, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Establece texto en todos los marcadores de posición de encabezado, incluidos el maestro de notas, las diapositivas de notas y el maestro de folletos. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Establece texto en todos los marcadores de posición de pie de página, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Establece texto en todos los marcadores de posición de fecha y hora, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Cambia la visibilidad de los marcadores de posición de pie de página, fecha y hora y número de diapositiva para todas las diapositivas de título y para la primera diapositiva de diseño. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Cambia la visibilidad de todos los marcadores de posición de encabezado, incluidos el maestro de notas, las diapositivas de notas y el maestro de folletos.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición del encabezado sean visibles, de lo contrario los oculta. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Cambia la visibilidad de todos los marcadores de posición de pie de página, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición del pie de página sean visibles, de lo contrario los oculta. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Cambia la visibilidad de todos los marcadores de posición de número de diapositiva, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición del número de diapositiva sean visibles, de lo contrario los oculta. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Cambia la visibilidad de todos los marcadores de posición de fecha y hora, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición de fecha y hora sean visibles, de lo contrario los oculta. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Establece texto en todos los marcadores de posición de encabezado, incluidos el maestro de notas, las diapositivas de notas y el maestro de folletos.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Establece texto en todos los marcadores de posición de pie de página, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Establece texto en todos los marcadores de posición de fecha y hora, incluidos las diapositivas maestras, las diapositivas de diseño y las diapositivas.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Cambia la visibilidad de los marcadores de posición de pie de página, fecha y hora y número de diapositiva para todas las diapositivas de título y para la primera diapositiva de diseño. Diapositivas de título – diapositivas basadas en la primera diapositiva de diseño (sin importar el tipo de esta primera diapositiva de diseño).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición sean visibles, de lo contrario los oculta. |