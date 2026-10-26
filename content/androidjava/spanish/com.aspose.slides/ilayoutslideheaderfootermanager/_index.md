---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa al gestor que mantiene el comportamiento de los marcadores de posición del pie de página, fecha y hora, número de página de la diapositiva de diseño y todos los marcadores de posición secundarios.
type: docs
url: /es/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representa el administrador que mantiene el comportamiento del marcador de posición de pie de página de la diapositiva de diseño, fecha y hora, número de página y todos los marcadores de posición secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño.
## Métodos

| Método | Descripción |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Cambia la visibilidad del marcador de posición de pie de página de la diapositiva de diseño y de todos los marcadores de posición de pie de página secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva maestra. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Cambia la visibilidad del marcador de posición de número de página de la diapositiva de diseño y de todos los marcadores de posición de número de página secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Cambia la visibilidad del marcador de posición de fecha y hora de la diapositiva de diseño y de todos los marcadores de posición de fecha y hora secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Establece texto en el marcador de posición de pie de página de la diapositiva de diseño y en todos los marcadores de posición de pie de página secundarios. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Establece texto en el marcador de posición de fecha y hora de la diapositiva de diseño y en todos los marcadores de posición de fecha y hora secundarios. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición de pie de página de la diapositiva de diseño y de todos los marcadores de posición de pie de página secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva maestra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición de pie de página sean visibles, de lo contrario los oculta. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición de número de página de la diapositiva de diseño y de todos los marcadores de posición de número de página secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición de número de página sean visibles, de lo contrario los oculta. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Cambia la visibilidad del marcador de posición de fecha y hora de la diapositiva de diseño y de todos los marcadores de posición de fecha y hora secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| isVisible | boolean | true - hace que los marcadores de posición de fecha y hora sean visibles, de lo contrario los oculta. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Establece texto en el marcador de posición de pie de página de la diapositiva de diseño y en todos los marcadores de posición de pie de página secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Establece texto en el marcador de posición de fecha y hora de la diapositiva de diseño y en todos los marcadores de posición de fecha y hora secundarios. Los marcadores de posición secundarios significan que los marcadores de posición están contenidos en diapositivas dependientes. Las diapositivas dependientes usan y dependen de la diapositiva de diseño.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| text | java.lang.String | Texto a establecer. |