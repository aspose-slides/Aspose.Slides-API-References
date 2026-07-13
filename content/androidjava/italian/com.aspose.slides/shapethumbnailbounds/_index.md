---
title: ShapeThumbnailBounds
second_title: Riferimento API Java di Aspose.Slides per Android
description: Enumerazione dei tipi di limiti della miniatura della forma.
type: docs
url: /it/com.aspose.slides/shapethumbnailbounds/
---
**Ereditarietà:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumerazione dei tipi di limiti della miniatura della forma.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Slide](#Slide) | La miniatura della forma avrà la dimensione pari alla dimensione della diapositiva. |
| [Shape](#Shape) | La miniatura della forma avrà la dimensione pari al rettangolo di delimitazione della forma, tenendo conto delle impostazioni del contorno della forma. |
| [Appearance](#Appearance) | La miniatura della forma avrà la dimensione pari all'aspetto della forma (nei limiti di una diapositiva). |
### Diapositiva {#Slide}
```
public static final int Slide
```

La miniatura della forma avrà la dimensione pari alla dimensione della diapositiva. La posizione della forma sarà salvata.

### Forma {#Shape}
```
public static final int Shape
```

La miniatura della forma avrà la dimensione pari al rettangolo di delimitazione della forma, tenendo conto delle impostazioni del contorno della forma.

### Aspetto {#Appearance}
```
public static final int Appearance
```

La miniatura della forma avrà la dimensione pari all'aspetto della forma (nei limiti di una diapositiva). Possono verificarsi casi in cui l'aspetto della forma non rientra nei limiti della forma. Ad esempio rotazione, giunzione a spigolo acuto, effetti 3D, ecc.