---
title: PictureFillFormat
second_title: Aspose.Slides für C++ API Referenz
description: Stellt einen Bildfüllstil dar.
type: docs
weight: 4720
url: /de/aspose.slides/picturefillformat/
---
## PictureFillFormat Klasse

Stellt einen Bildfüllstil dar.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch beschnittene Bereiche. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Komprimiert das Bild, indem es seine Größe basierend auf der Formgröße und der angegebenen Auflösung reduziert. Optional löscht es auch beschnittene Bereiche. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Löscht beschnittene Bereiche der Füllung [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Vergleicht mit dem angegebenen Objekt. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkomma-Vergleich, bei dem zwei NaN-Werte als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Gibt die prozentuale Höhe des echten Bildes zurück, die am unteren Rand des Bildes beschnitten ist. Lese **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Gibt den prozentualen Anteil der echten Bildbreite zurück, der am linken Rand des Bildes beschnitten ist. Lese **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Gibt den prozentualen Anteil der echten Bildbreite zurück, der am rechten Rand des Bildes beschnitten ist. Lese **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Gibt die prozentuale Höhe des echten Bildes zurück, die am oberen Rand des Bildes beschnitten ist. Lese **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Gibt die DPI zurück, die zum Füllen eines Bildes verwendet wird. Lese **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Gibt das Parent_Immediate-Objekt zurück. Nur-Lesen [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Gibt das übergeordnete [IPresentationComponent](../ipresentationcomponent/) zurück. Nur-Lesen [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Gibt das Bild zurück. Nur-Lesen [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Gibt den Bildfüllmodus zurück. Lese [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Gibt die untere Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz gibt einen Überstand an. Lese **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Gibt die linke Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz gibt einen Überstand an. Lese **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Gibt die rechte Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz gibt einen Überstand an. Lese **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Gibt die obere Kante des Füllrechtecks zurück, das durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz gibt einen Überstand an. Lese **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Gibt zurück, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Ausgangspunkt des Textur-Musters und wie es über die Form wiederholt wird. Lese [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Spiegelt das Textur-Kachel horizontal, vertikal oder um beide Achsen. Lese [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Gibt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert nach links. Lese **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Gibt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten zurück. Ein positiver Wert verschiebt die Textur nach unten, ein negativer Wert nach oben. Lese **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Gibt die horizontale Skalierung der Texturfüllung als Prozentsatz zurück. Lese **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Gibt die vertikale Skalierung der Texturfüllung als Prozentsatz zurück. Lese **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Erhält die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Gibt den Hash-Code zurück. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Erhält den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren gemäß C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|   [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|   [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert eigentlich nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Setzt den prozentualen Anteil der echten Bildhöhe, der am unteren Rand des Bildes beschnitten wird. Schreibe **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Setzt den prozentualen Anteil der echten Bildbreite, der am linken Rand des Bildes beschnitten wird. Schreibe **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Setzt den prozentualen Anteil der echten Bildbreite, der am rechten Rand des Bildes beschnitten wird. Schreibe **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Setzt den prozentualen Anteil der echten Bildhöhe, der am oberen Rand des Bildes beschnitten wird. Schreibe **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Setzt die DPI, die zum Füllen eines Bildes verwendet wird. Schreibe **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Setzt den Bildfüllmodus. Schreibe [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Setzt die untere Kante des Füllrechtecks, das durch einen prozentualen Versatz von der unteren Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Überstand. Schreibe **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Setzt die linke Kante des Füllrechtecks, das durch einen prozentualen Versatz von der linken Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Überstand. Schreibe **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Setzt die rechte Kante des Füllrechtecks, das durch einen prozentualen Versatz von der rechten Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Überstand. Schreibe **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Setzt die obere Kante des Füllrechtecks, das durch einen prozentualen Versatz von der oberen Kante der Begrenzungsbox der Form definiert ist. Ein positiver Prozentsatz gibt einen Einzug an, ein negativer Prozentsatz einen Überstand. Schreibe **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Setzt, wie die Textur innerhalb der Form ausgerichtet ist. Diese Einstellung bestimmt den Ausgangspunkt des Textur-Musters und wie es über die Form wiederholt wird. Schreibe [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Spiegelt die Texturkachel horizontal, vertikal oder um beide Achsen. Schreibe [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Setzt den horizontalen Versatz der Textur vom Ursprung der Form in Punkten. Ein positiver Wert verschiebt die Textur nach rechts, ein negativer Wert nach links. Schreibe **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Setzt den vertikalen Versatz der Textur vom Ursprung der Form in Punkten. Ein positiver Wert verschiebt die Textur nach unten, ein negativer Wert nach oben. Schreibe **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Setzt die horizontale Skalierung der Texturfüllung als Prozentsatz. Schreibe **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Setzt die vertikale Skalierung der Texturfüllung als Prozentsatz. Schreibe **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen Weak-Pointer (statt Shared). Ermöglicht das Umlagern von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Erhält den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren gemäß C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [PVIObject](../pviobject/)
* Klasse [IPictureFillFormat](../ipicturefillformat/)
* Namespace [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)