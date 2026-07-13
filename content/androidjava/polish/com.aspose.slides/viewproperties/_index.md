---
title: ViewProperties
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Właściwości widoku na poziomie prezentacji.
type: docs
url: /pl/com.aspose.slides/viewproperties/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IViewProperties](../../com.aspose.slides/iviewproperties), com.aspose.slides.IDOMObject
```
public class ViewProperties implements IViewProperties, IDOMObject
```

Właściwości widoku na poziomie prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLastView()](#getLastView--) | Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. |
| [setLastView(int value)](#setLastView-int-) | Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. |
| [getShowComments()](#getShowComments--) | Określa, czy komentarze slajdu powinny być wyświetlane. |
| [setShowComments(byte value)](#setShowComments-byte-) | Określa, czy komentarze slajdu powinny być wyświetlane. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Reprezentuje właściwości normalnego widoku. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Określa wspólne właściwości widoku powiązane z trybem widoku slajdu. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Określa wspólne właściwości widoku powiązane z trybem widoku notatek. |
| [getGridSpacing()](#getGridSpacing--) | Zwraca lub ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Zwraca lub ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getLastView() {#getLastView--}
```
public final int getLastView()
```

Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. Odczyt/zapis [ViewType](../../com.aspose.slides/viewtype).

**Zwraca:**
int

### setLastView(int value) {#setLastView-int-}
```
public final void setLastView(int value)
```

Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. Odczyt/zapis [ViewType](../../com.aspose.slides/viewtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public final byte getShowComments()
```

Określa, czy komentarze slajdu powinny być wyświetlane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setShowComments(byte value) {#setShowComments-byte-}
```
public final void setShowComments(byte value)
```

Określa, czy komentarze slajdu powinny być wyświetlane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getNormalViewProperties() {#getNormalViewProperties--}
```
public final INormalViewProperties getNormalViewProperties()
```

Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech regionów treści: samego slajdu, bocznego regionu treści oraz dolnego regionu treści. Tylko do odczytu [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Zwraca:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)

### getSlideViewProperties() {#getSlideViewProperties--}
```
public final ICommonSlideViewProperties getSlideViewProperties()
```

Określa wspólne właściwości widoku powiązane z trybem widoku slajdu. Tylko do odczytu [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Zwraca:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getNotesViewProperties() {#getNotesViewProperties--}
```
public final ICommonSlideViewProperties getNotesViewProperties()
```

Określa wspólne właściwości widoku powiązane z trybem widoku notatek. Tylko do odczytu [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Zwraca:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)

### getGridSpacing() {#getGridSpacing--}
```
public final float getGridSpacing()
```

Zwraca lub ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. Odczyt/zapis float.

--------------------

> ```
> Poniższy przykładowy kod pokazuje, jak zmienić odstęp siatki w prezentacji PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Wartość odstępu siatki musi być liczbą dodatnią. Typowy zakres wartości wynosi od 1 mm (2.8349607 punktów) do 2 cali (144 punkty).

**Zwraca:**
float

### setGridSpacing(float value) {#setGridSpacing-float-}
```
public final void setGridSpacing(float value)
```

Zwraca lub ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. Odczyt/zapis float.

--------------------

> ```
> Poniższy przykładowy kod pokazuje, jak zmienić odstęp siatki w prezentacji PowerPoint.
>  
>  Presentation pres = new Presentation();
>  try {
>      pres.getViewProperties().setGridSpacing(72f);
>      pres.save("GridSpacing_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Wartość odstępu siatki musi być liczbą dodatnią. Typowy zakres wartości wynosi od 1 mm (2.8349607 punktów) do 2 cali (144 punkty).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject