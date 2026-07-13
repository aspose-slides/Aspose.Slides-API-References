---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Zawiera właściwości formatowania TextFrames.
type: docs
url: /pl/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Zawiera właściwości formatowania TextFrame.
## Metody

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Zwraca styl tekstu. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lub ustawia lewy margines (punkty) w TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Zwraca lub ustawia lewy margines (punkty) w TextFrame. |
| [getMarginRight()](#getMarginRight--) | Zwraca lub ustawia prawy margines (punkty) w TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Zwraca lub ustawia prawy margines (punkty) w TextFrame. |
| [getMarginTop()](#getMarginTop--) | Zwraca lub ustawia górny margines (punkty) w TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Zwraca lub ustawia górny margines (punkty) w TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Zwraca lub ustawia dolny margines (punkty) w TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Zwraca lub ustawia dolny margines (punkty) w TextFrame. |
| [getWrapText()](#getWrapText--) | Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Zwraca lub ustawia pionowy punkt zaczepienia tekstu w TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Zwraca lub ustawia pionowy punkt zaczepienia tekstu w TextFrame. |
| [getCenterText()](#getCenterText--) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. |
| [getTextVerticalType()](#getTextVerticalType--) | Określa orientację tekstu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Określa orientację tekstu. |
| [getAutofitType()](#getAutofitType--) | Zwraca lub ustawia tryb automatycznego dopasowania tekstu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Zwraca lub ustawia tryb automatycznego dopasowania tekstu. |
| [getColumnCount()](#getColumnCount--) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. |
| [setColumnCount(int value)](#setColumnCount-int-) | Zwraca lub ustawia liczbę kolumn w obszarze tekstu. |
| [getColumnSpacing()](#getColumnSpacing--) | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). |
| [getThreeDFormat()](#getThreeDFormat--) | Zwraca obiekt ThreeDFormat reprezentujący właściwości efektu 3D dla tekstu. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Zwraca lub ustawia pełne wykluczenie tekstu ze sceny 3D. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Zwraca lub ustawia pełne wykluczenie tekstu ze sceny 3D. |
| [getRotationAngle()](#getRotationAngle--) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. |
| [getTransform()](#getTransform--) | Pobiera lub ustawia kształt zawijania tekstu. |
| [setTransform(byte value)](#setTransform-byte-) | Pobiera lub ustawia kształt zawijania tekstu. |
| [getEffective()](#getEffective--) | Pobiera efektywne dane formatowania ramki tekstowej z zastosowanym dziedziczeniem. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Zwraca styl tekstu. Tylko do odczytu [ITextStyle](../../com.aspose.slides/itextstyle).

**Zwraca:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Zwraca lub ustawia lewy margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Zwraca lub ustawia lewy margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Zwraca lub ustawia prawy margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Zwraca lub ustawia prawy margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Zwraca lub ustawia górny margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Zwraca lub ustawia górny margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Zwraca lub ustawia dolny margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Zwraca:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Zwraca lub ustawia dolny margines (punkty) w TextFrame. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Do odczytu i zapisu [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Do odczytu i zapisu [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Zwraca lub ustawia pionowy punkt zaczepienia tekstu w TextFrame. Do odczytu i zapisu [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Zwraca lub ustawia pionowy punkt zaczepienia tekstu w TextFrame. Do odczytu i zapisu [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. Do odczytu i zapisu [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w ramce. Do odczytu i zapisu [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i wstępnie zdefiniowanego typu pionowego w właściwości TextVerticalType. Do odczytu i zapisu [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i wstępnie zdefiniowanego typu pionowego w właściwości TextVerticalType. Do odczytu i zapisu [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Zwraca lub ustawia tryb automatycznego dopasowania tekstu. Do odczytu i zapisu [TextAutofitType](../../com.aspose.slides/textautofittype).

**Zwraca:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Zwraca lub ustawia tryb automatycznego dopasowania tekstu. Do odczytu i zapisu [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Ta wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Do odczytu i zapisu int.

**Zwraca:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


Zwraca lub ustawia liczbę kolumn w obszarze tekstu. Ta wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Wartość 0 oznacza nieokreśloną wartość. Do odczytu i zapisu int.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Dotyczy to tylko przypadków, gdy istnieje więcej niż 1 kolumna. Ta wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Do odczytu i zapisu double.

**Zwraca:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Zwraca lub ustawia odstęp między kolumnami tekstu w obszarze tekstu (w punktach). Dotyczy to tylko przypadków, gdy istnieje więcej niż 1 kolumna. Ta wartość musi być liczbą dodatnią. W przeciwnym razie zostanie ustawiona na zero. Do odczytu i zapisu double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Zwraca obiekt ThreeDFormat reprezentujący właściwości efektu 3D dla tekstu. Tylko do odczytu [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ustaw transformację tekstu
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ustaw ekstruzję
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Ustaw kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Ustaw głębokość
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Ustaw materiał
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Ustaw oświetlenie
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Ustaw typ kamery
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```


Zwraca lub ustawia pełne wykluczenie tekstu ze sceny 3D. Do odczytu i zapisu boolean.

**Zwraca:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Zwraca lub ustawia pełne wykluczenie tekstu ze sceny 3D. Do odczytu i zapisu boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. Jeśli nie jest określony, używany jest obrót powiązanego kształtu. Jeśli jest określony, jest stosowany niezależnie od kształtu. To znaczy, że kształt może mieć zastosowany obrót oprócz tego, że sam tekst ma zastosowany obrót. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i wstępnie zdefiniowanego typu pionowego w właściwości TextVerticalType. Do odczytu i zapisu float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```


**Zwraca:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Określa niestandardowy obrót stosowany do tekstu w obrębie ramki ograniczającej. Jeśli nie jest określony, używany jest obrót powiązanego kształtu. Jeśli jest określony, jest stosowany niezależnie od kształtu. To znaczy, że kształt może mieć zastosowany obrót oprócz tego, że sam tekst ma zastosowany obrót. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i wstępnie zdefiniowanego typu pionowego w właściwości TextVerticalType. Do odczytu i zapisu float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


Pobiera lub ustawia kształt zawijania tekstu. Do odczytu i zapisu [TextShapeType](../../com.aspose.slides/textshapetype).

**Zwraca:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


Pobiera lub ustawia kształt zawijania tekstu. Do odczytu i zapisu [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


Pobiera efektywne dane formatowania ramki tekstowej z zastosowanym dziedziczeniem.

**Zwraca:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).