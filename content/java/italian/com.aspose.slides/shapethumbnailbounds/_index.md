---
title: ShapeThumbnailBounds
second_title: Riferimento API di Aspose.Slides per Java
description: Enumerazione dei tipi di limiti dell'anteprima della forma.
type: docs
url: /it/com.aspose.slides/shapethumbnailbounds/
---
**Eredità:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ShapeThumbnailBounds extends System.Enum
```

Enumerazione dei tipi di limiti dell'anteprima della forma.
## Campi

| Campo | Descrizione |
| --- | --- |
| [Slide](#Slide) | L'anteprima della forma avrà le dimensioni uguali a quelle della diapositiva. |
| [Shape](#Shape) | L'anteprima della forma avrà le dimensioni uguali al rettangolo dei limiti della forma tenendo conto delle impostazioni del contorno della forma. |
| [Appearance](#Appearance) | L'anteprima della forma avrà le dimensioni uguali all'aspetto della forma (all'interno dei limiti di una diapositiva). |
### Diapositiva {#Slide}
```
public static final int Slide
```

L'anteprima della forma avrà le dimensioni uguali a quelle della diapositiva. La posizione della forma verrà salvata.

### Forma {#Shape}
```
public static final int Shape
```

L'anteprima della forma avrà le dimensioni uguali al rettangolo dei limiti della forma tenendo conto delle impostazioni del contorno della forma.

### Aspetto {#Appearance}
```
public static final int Appearance
```

L'anteprima della forma avrà le dimensioni uguali all'aspetto della forma (all'interno dei limiti di una diapositiva). Possono verificarsi casi in cui l'aspetto della forma non rientra nei limiti della forma. Per es., rotazione, unione a spigolo di angolo acuto, effetti 3D, ecc.