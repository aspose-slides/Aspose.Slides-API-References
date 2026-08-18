---
title: IViewProperties
second_title: Aspose.Slides dla Java – odniesienie API
description: Właściwości widoku na poziomie całej prezentacji.
type: docs
url: /pl/com.aspose.slides/iviewproperties/
---```
public interface IViewProperties
```

Właściwości widoku na poziomie całej prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getLastView()](#getLastView--) | Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. |
| [setLastView(int value)](#setLastView-int-) | Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. |
| [getShowComments()](#getShowComments--) | Określa, czy komentarze slajdu powinny być wyświetlane. |
| [setShowComments(byte value)](#setShowComments-byte-) | Określa, czy komentarze slajdu powinny być wyświetlane. |
| [getSlideViewProperties()](#getSlideViewProperties--) | Określa wspólne właściwości widoku powiązane z trybem widoku slajdu. |
| [getNotesViewProperties()](#getNotesViewProperties--) | Określa wspólne właściwości widoku powiązane z trybem widoku notatek. |
| [getNormalViewProperties()](#getNormalViewProperties--) | Reprezentuje właściwości normalnego widoku. |
| [getGridSpacing()](#getGridSpacing--) | Zwraca lub ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. |
| [setGridSpacing(float value)](#setGridSpacing-float-) | Zwraca lub ustawia odstęp siatki, który powinien być używany dla siatki leżącej u podstaw dokumentu prezentacji, w punktach. |
### getLastView() {#getLastView--}
```
public abstract int getLastView()
```

Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. Odczyt/zapis [ViewType](../../com.aspose.slides/viewtype).

**Zwraca:**
int
### setLastView(int value) {#setLastView-int-}
```
public abstract void setLastView(int value)
```

Określa tryb widoku, który był używany, gdy dokument prezentacji został ostatnio zapisany. Odczyt/zapis [ViewType](../../com.aspose.slides/viewtype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getShowComments() {#getShowComments--}
```
public abstract byte getShowComments()
```

Określa, czy komentarze slajdu powinny być wyświetlane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setShowComments(byte value) {#setShowComments-byte-}
```
public abstract void setShowComments(byte value)
```

Określa, czy komentarze slajdu powinny być wyświetlane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getSlideViewProperties() {#getSlideViewProperties--}
```
public abstract ICommonSlideViewProperties getSlideViewProperties()
```

Określa wspólne właściwości widoku powiązane z trybem widoku slajdu. Tylko do odczytu [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Zwraca:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNotesViewProperties() {#getNotesViewProperties--}
```
public abstract ICommonSlideViewProperties getNotesViewProperties()
```

Określa wspólne właściwości widoku powiązane z trybem widoku notatek. Tylko do odczytu [ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties).

**Zwraca:**
[ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
### getNormalViewProperties() {#getNormalViewProperties--}
```
public abstract INormalViewProperties getNormalViewProperties()
```

Reprezentuje właściwości normalnego widoku. Normalny widok składa się z trzech obszarów treści: samego slajdu, bocznego obszaru treści oraz dolnego obszaru treści. Tylko do odczytu [INormalViewProperties](../../com.aspose.slides/inormalviewproperties).

**Zwraca:**
[INormalViewProperties](../../com.aspose.slides/inormalviewproperties)
### getGridSpacing() {#getGridSpacing--}
```
public abstract float getGridSpacing()
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

Wartość odstępu siatki musi być liczbą dodatnią. Typowy zakres wynosi od 1 mm (2,8349607 punktu) do 2 cali (144 punktów).

**Zwraca:**
float
### setGridSpacing(float value) {#setGridSpacing-float-}
```
public abstract void setGridSpacing(float value)
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

Wartość odstępu siatki musi być liczbą dodatnią. Typowy zakres wynosi od 1 mm (2,8349607 punktu) do 2 cali (144 punktów).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |