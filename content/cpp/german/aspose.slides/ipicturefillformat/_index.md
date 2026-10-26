---
title: IPictureFillFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 3225
url: /de/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat Klasse


Stellt einen Bildfüllstil dar.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden dabei auch beschnittene Bereiche gelöscht. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Komprimiert das Bild, indem seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert wird. Optional werden dabei auch beschnittene Bereiche gelöscht. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Löscht beschnittene Bereiche der Füllung [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleich von Referenztyp-Objekten im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleich von Werttyp-Objekten im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Gibt die Prozentzahl der realen Bildhöhe zurück, die am unteren Rand des Bildes abgeschnitten wird. Lese **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Gibt die Prozentzahl der realen Bildbreite zurück, die am linken Rand des Bildes abgeschnitten wird. Lese **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Gibt die Prozentzahl der realen Bildbreite zurück, die am rechten Rand des Bildes abgeschnitten wird. Lese **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Gibt die Prozentzahl der realen Bildhöhe zurück, die am oberen Rand des Bildes abgeschnitten wird. Lese **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Gibt die DPI zurück, die zum Füllen eines Bildes verwendet wird. Lese **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Gibt das Bild zurück. Nur lesend [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Gibt den Bildfüllmodus zurück. Nur [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Gibt die untere Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Lese **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Gibt die linke Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Lese **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Gibt die rechte Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Lese **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Gibt die obere Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Lese **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Startpunkt des Texturmusters und dessen Wiederholung über die Form hinweg. Lese [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Dreht das Textur-Tile um seine horizontale, vertikale oder beide Achsen. Lese [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert nach links. Lese **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach unten, ein negativer Wert nach oben. Lese **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Gibt den horizontalen Maßstab für die Texturfüllung als Prozentsatz zurück. Lese **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Gibt den vertikalen Maßstab für die Texturfüllung als Prozentsatz zurück. Lese **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die C# lock()-Anweisung zum Sperren. Direkter Aufruf oder Verwendung des [LockContext](../../system/lockcontext/)-Wächterobjekts. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, initialisiert nur ein neues Objekt und ermöglicht das Kopier-Konstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisation von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisation von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsam genutzte Referenzzählung um den angegebenen Wert. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Setzt die Prozentzahl der realen Bildhöhe, die am unteren Rand des Bildes abgeschnitten wird. Schreibe **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Setzt die Prozentzahl der realen Bildbreite, die am linken Rand des Bildes abgeschnitten wird. Schreibe **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Setzt die Prozentzahl der realen Bildbreite, die am rechten Rand des Bildes abgeschnitten wird. Schreibe **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Setzt die Prozentzahl der realen Bildhöhe, die am oberen Rand des Bildes abgeschnitten wird. Schreibe **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Setzt die DPI, die zum Füllen eines Bildes verwendet wird. Schreibe **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Setzt den Bildfüllmodus. Schreibe [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Setzt die untere Kante des Füllrechtecks, das durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Schreibe **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Setzt die linke Kante des Füllrechtecks, das durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Schreibe **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Setzt die rechte Kante des Füllrechtecks, das durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Schreibe **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Setzt die obere Kante des Füllrechtecks, das durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz bedeutet Einzug, ein negativer Prozentsatz Ausstülpung. Schreibe **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Setzt, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung steuert den Startpunkt des Texturmusters und dessen Wiederholung über die Form hinweg. Schreibe [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Dreht das Textur-Tile um seine horizontale, vertikale oder beide Achsen. Schreibe [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Setzt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert nach links. Schreibe **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Setzt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten. Ein positiver Wert verschiebt die Textur nach unten, ein negativer Wert nach oben. Schreibe **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Setzt den horizontalen Maßstab für die Texturfüllung als Prozentsatz. Schreibe **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Setzt den vertikalen Maßstab für die Texturfüllung als Prozentsatz. Schreibe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem schwachen Zeiger (statt einem geteilten). Ermöglicht das Wechseln von Zeigern in Containern auf schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert die C# lock()-Anweisung zum Entsperren. Direkter Aufruf oder Verwendung des [LockContext](../../system/lockcontext/)-Wächterobjekts. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |
## Siehe auch

* Klasse [IFillParamSource](../ifillparamsource/)
* Namespace [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)