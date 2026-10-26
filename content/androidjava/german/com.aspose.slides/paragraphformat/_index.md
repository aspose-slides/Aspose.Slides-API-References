---
title: ParagraphFormat
second_title: Aspose.Slides für Android via Java API Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften.
type: docs
url: /de/com.aspose.slides/paragraphformat/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IParagraphFormat](../../com.aspose.slides/iparagraphformat), [com.aspose.slides.IChartParagraphFormat](../../com.aspose.slides/ichartparagraphformat)
```
public final class ParagraphFormat extends PVIObject implements IParagraphFormat, IChartParagraphFormat
```

Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) sind alle Eigenschaften dieser Klasse schreibbar.

--------------------

Diese Klasse wird verwendet, um die für den jeweiligen Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass bei der Abfrage von Werten keine Vererbung angewendet wird, sodass Sie in den meisten Fällen Werte erhalten, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die [getEffective](../../com.aspose.slides/paragraphformat\#getEffective)-Methode verwenden, die eine [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)-Instanz zurückgibt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [ParagraphFormat()](#ParagraphFormat--) | Initialisiert eine neue Instanz der Klasse [ParagraphFormat](../../com.aspose.slides/paragraphformat). |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBullet()](#getBullet--) | Gibt das Aufzählungsformat des Absatzes zurück. |
| [getDepth()](#getDepth--) | Gibt die Tiefe des Absatzes zurück oder legt sie fest. |
| [setDepth(short value)](#setDepth-short-) | Gibt die Tiefe des Absatzes zurück oder legt sie fest. |
| [getAlignment()](#getAlignment--) | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. |
| [setAlignment(int value)](#setAlignment-int-) | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. |
| [getSpaceWithin()](#getSpaceWithin--) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. |
| [getSpaceBefore()](#getSpaceBefore--) | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [getSpaceAfter()](#getSpaceAfter--) | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. |
| [getRightToLeft()](#getRightToLeft--) | Ermittelt, ob der Rechts-nach-Links-Schreibmodus in einem Absatz verwendet wird. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Ermittelt, ob der Rechts-nach-Links-Schreibmodus in einem Absatz verwendet wird. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Ermittelt, ob der lateinische Zeilenbruch in einem Absatz verwendet wird. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Ermittelt, ob der lateinische Zeilenbruch in einem Absatz verwendet wird. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. |
| [getMarginLeft()](#getMarginLeft--) | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [getMarginRight()](#getMarginRight--) | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [setMarginRight(float value)](#setMarginRight-float-) | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. |
| [getIndent()](#getIndent--) | Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. |
| [setIndent(float value)](#setIndent-float-) | Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder legt sie fest. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder legt sie fest. |
| [getTabs()](#getTabs--) | Gibt die Tabulatoren eines Absatzes zurück. |
| [getFontAlignment()](#getFontAlignment--) | Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Gibt das Standardabschnittsformat eines Absatzes zurück. |
| [getEffective()](#getEffective--) | Ermittelt die effektiven Absatzformatierungsdaten mit angewandter Vererbung. |
| [getVersion()](#getVersion--) |  |
### ParagraphFormat() {#ParagraphFormat--}
```
public ParagraphFormat()
```

Initialisiert eine neue Instanz der Klasse [ParagraphFormat](../../com.aspose.slides/paragraphformat).

### getBullet() {#getBullet--}
```
public final IBulletFormat getBullet()
```

Gibt das Aufzählungsformat des Absatzes zurück. Nur lesend [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Rückgabe:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)
### getDepth() {#getDepth--}
```
public final short getDepth()
```

Gibt die Tiefe des Absatzes zurück oder legt sie fest. Der Wert 0 bedeutet undefiniert. Lesen/Schreiben short .

**Rückgabe:**
short
### setDepth(short value) {#setDepth-short-}
```
public final void setDepth(short value)
```

Gibt die Tiefe des Absatzes zurück oder legt sie fest. Der Wert 0 bedeutet undefiniert. Lesen/Schreiben short .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | short |  |
### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```

Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanziieren Sie ein Presentation-Objekt, das eine PPTX-Datei darstellt
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Zugriff auf die erste Folie
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Zugriff auf den ersten und zweiten Platzhalter in der Folie und Typumwandlung in AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Ändern des Textes in beiden Platzhaltern
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Abrufen des ersten Absatzes der Platzhalter
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Ausrichten des Textabsatzes zur Mitte
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Schreiben der Präsentation als PPTX-Datei
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```

Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [TextAlignment](../../com.aspose.slides/textalignment).

--------------------

> ```
> The following sample code shows how to Align Text Paragraphs in PowerPoint Presentation.
>  
>  // Instanziieren Sie ein Presentation-Objekt, das eine PPTX-Datei darstellt
>  Presentation pres = new Presentation("ParagraphsAlignment.pptx");
>  try {
>      // Zugriff auf die erste Folie
>      ISlide slide = pres.getSlides().get_Item(0);
>      // Zugriff auf den ersten und zweiten Platzhalter in der Folie und Typumwandlung in AutoShape
>      ITextFrame tf1 = ((IAutoShape)slide.getShapes().get_Item(0)).getTextFrame();
>      ITextFrame tf2 = ((IAutoShape)slide.getShapes().get_Item(1)).getTextFrame();
>      // Ändern Sie den Text in beiden Platzhaltern
>      tf1.setText("Center Align by Aspose");
>      tf2.setText("Center Align by Aspose");
>      // Abrufen des ersten Absatzes der Platzhalter
>      IParagraph para1 = tf1.getParagraphs().get_Item(0);
>      IParagraph para2 = tf2.getParagraphs().get_Item(0);
>      // Ausrichten des Textabsatzes zur Mitte
>      para1.getParagraphFormat().setAlignment(TextAlignment.Center);
>      para2.getParagraphFormat().setAlignment(TextAlignment.Center);
>      // Schreiben der Präsentation als PPTX-Datei
>      pres.save("Centeralign_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSpaceWithin() {#getSpaceWithin--}
```
public final float getSpaceWithin()
```

Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Ein positiver Wert bedeutet Prozentsatz, ein negativer – Größe in Punkten. Keine Vererbung angewendet. Lesen/Schreiben float .

**Rückgabe:**
float
### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public final void setSpaceWithin(float value)
```

Gibt den Abstand zwischen Grundlinien in einem Absatz zurück oder legt ihn fest. Ein positiver Wert bedeutet Prozentsatz, ein negativer – Größe in Punkten. Keine Vererbung angewendet. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getSpaceBefore() {#getSpaceBefore--}
```
public final float getSpaceBefore()
```

Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben float .

**Rückgabe:**
float
### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public final void setSpaceBefore(float value)
```

Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getSpaceAfter() {#getSpaceAfter--}
```
public final float getSpaceAfter()
```

Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben float .

**Rückgabe:**
float
### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public final void setSpaceAfter(float value)
```

Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück oder legt ihn fest. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public final byte getEastAsianLineBreak()
```

Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public final void setEastAsianLineBreak(byte value)
```

Ermittelt, ob der ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getRightToLeft() {#getRightToLeft--}
```
public final byte getRightToLeft()
```

Ermittelt, ob der Rechts-nach-Links-Schreibmodus in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public final void setRightToLeft(byte value)
```

Ermittelt, ob der Rechts-nach-Links-Schreibmodus in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getLatinLineBreak() {#getLatinLineBreak--}
```
public final byte getLatinLineBreak()
```

Ermittelt, ob der lateinische Zeilenbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public final void setLatinLineBreak(byte value)
```

Ermittelt, ob der lateinische Zeilenbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getHangingPunctuation() {#getHangingPunctuation--}
```
public final byte getHangingPunctuation()
```

Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public final void setHangingPunctuation(byte value)
```

Ermittelt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getMarginLeft() {#getMarginLeft--}
```
public final float getMarginLeft()
```

Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben float .

**Rückgabe:**
float
### setMarginLeft(float value) {#setMarginLeft-float-}
```
public final void setMarginLeft(float value)
```

Gibt den linken Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getMarginRight() {#getMarginRight--}
```
public final float getMarginRight()
```

Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben float .

**Rückgabe:**
float
### setMarginRight(float value) {#setMarginRight-float-}
```
public final void setMarginRight(float value)
```

Gibt den rechten Rand in einem Absatz ohne Vererbung zurück oder legt ihn fest. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getIndent() {#getIndent--}
```
public final float getIndent()
```

Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. Der hängende Einzug kann mit negativen Werten definiert werden. Lesen/Schreiben float .

**Rückgabe:**
float
### setIndent(float value) {#setIndent-float-}
```
public final void setIndent(float value)
```

Gibt den Erstzeileneinzug/Hängenden Einzug des Absatzes ohne Vererbung zurück oder legt ihn fest. Der hängende Einzug kann mit negativen Werten definiert werden. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getDefaultTabSize() {#getDefaultTabSize--}
```
public final float getDefaultTabSize()
```

Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben float .

**Rückgabe:**
float
### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public final void setDefaultTabSize(float value)
```

Gibt die Standard-Tabulatorgröße ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben float .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getTabs() {#getTabs--}
```
public final ITabCollection getTabs()
```

Gibt die Tabulatoren eines Absatzes zurück. Keine Vererbung angewendet. Nur lesend [ITabCollection](../../com.aspose.slides/itabcollection).

**Rückgabe:**
[ITabCollection](../../com.aspose.slides/itabcollection)
### getFontAlignment() {#getFontAlignment--}
```
public final int getFontAlignment()
```

Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [FontAlignment](../../com.aspose.slides/fontalignment).

**Rückgabe:**
int
### setFontAlignment(int value) {#setFontAlignment-int-}
```
public final void setFontAlignment(int value)
```

Gibt die Schriftartausrichtung in einem Absatz ohne Vererbung zurück oder legt sie fest. Lesen/Schreiben [FontAlignment](../../com.aspose.slides/fontalignment).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public final IPortionFormat getDefaultPortionFormat()
```

Gibt das Standardabschnittsformat eines Absatzes zurück. Keine Vererbung angewendet. Nur lesend [IPortionFormat](../../com.aspose.slides/iportionformat).

**Rückgabe:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### getEffective() {#getEffective--}
```
public final IParagraphFormatEffectiveData getEffective()
```

Ermittelt die effektiven Absatzformatierungsdaten mit angewandter Vererbung.

--------------------

> ```
> Dieses Beispiel demonstriert das Abrufen einiger effektiver Absatzformat-Eigenschaften.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IParagraphFormatEffectiveData effectiveParagraphFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getEffective();
>  	System.out.println("Text alignment: " + effectiveParagraphFormat.getAlignment());
>  	System.out.println("Indent: " + effectiveParagraphFormat.getIndent());
>  	System.out.println("Bullet type: " + effectiveParagraphFormat.getBullet().getType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Rückgabe:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Nur lesend long.

**Rückgabe:**
long