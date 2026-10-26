---
title: IMasterSlideHeaderFooterManager
second_title: Referencia de API Java de Aspose.Slides para Android
description: Representa al gestor que mantiene el comportamiento de los marcadores de posición del pie de página, fecha y hora, número de página de la diapositiva maestra y de todos los marcadores de posición hijos.
type: docs
url: /es/com.aspose.slides/imasterslideheaderfootermanager/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representa al gestor que mantiene el comportamiento del pie de página de la diapositiva maestra, los marcadores de posición de fecha y hora, número de página y todos los marcadores de posición hijos. Los marcadores de posición hijos son marcadores que están contenidos en diapositivas de diseño dependientes y en diapositivas dependientes. Las diapositivas de diseño dependientes y las diapositivas usan y dependen de la diapositiva maestra.

## Métodos

| Método | Descripción |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Cambia la visibilidad del marcador de posición del pie de página de la diapositiva maestra y de todos los marcadores de posición de pie de página hijos. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Cambia la visibilidad del marcador de posición del número de página de la diapositiva maestra y de todos los marcadores de posición de número de página hijos. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Cambia la visibilidad del marcador de posición de fecha y hora de la diapositiva maestra y de todos los marcadores de posición de fecha y hora hijos. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Establece el texto del marcador de posición del pie de página de la diapositiva maestra y de todos los marcadores de posición de pie de página hijos. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Establece el texto del marcador de posición de fecha y hora de la diapositiva maestra y de todos los marcadores de posición de fecha y hora hijos. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición del pie de página de la diapositiva maestra y de todos los marcadores de posición de pie de página hijos. Los marcadores de posición hijos son marcadores que están contenidos en diapositivas de diseño dependientes y en diapositivas dependientes. Las diapositivas de diseño dependientes y las diapositivas usan y dependen de la diapositiva maestra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición del pie de página sean visibles, de lo contrario los oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición del número de página de la diapositiva maestra y de todos los marcadores de posición de número de página hijos. Los marcadores de posición hijos son marcadores que están contenidos en diapositivas de diseño dependientes y en diapositivas dependientes. Las diapositivas de diseño dependientes y las diapositivas usan y dependen de la diapositiva maestra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición del número de página sean visibles, de lo contrario los oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición de fecha y hora de la diapositiva maestra y de todos los marcadores de posición de fecha y hora hijos. Los marcadores de posición hijos son marcadores que están contenidos en diapositivas de diseño dependientes y en diapositivas dependientes. Las diapositivas de diseño dependientes y las diapositivas usan y dependen de la diapositiva maestra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición de fecha y hora sean visibles, de lo contrario los oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Establece el texto del marcador de posición del pie de página de la diapositiva maestra y de todos los marcadores de posición de pie de página hijos. Los marcadores de posición hijos son marcadores que están contenidos en diapositivas de diseño dependientes y en diapositivas dependientes. Las diapositivas de diseño dependientes y las diapositivas usan y dependen de la diapositiva maestra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Establece el texto del marcador de posición de fecha y hora de la diapositiva maestra y de todos los marcadores de posición de fecha y hora hijos. Los marcadores de posición hijos son marcadores que están contenidos en diapositivas de diseño dependientes y en diapositivas dependientes. Las diapositivas de diseño dependientes y las diapositivas usan y dependen de la diapositiva maestra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |