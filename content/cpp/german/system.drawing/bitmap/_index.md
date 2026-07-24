---
title: Bitmap
second_title: "Aspose.Slides für C++ API Referenz"
description: "Stellt ein GDI+ Bitmap-Bild dar. Objekte dieser Klasse sollten nur mit der Funktion System::MakeObject() zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 1
url: /de/system.drawing/bitmap/
---
## Bitmap Klasse


Stellt ein GDI+ Bitmap-Bild dar. Objekte dieser Klasse sollten nur mit der Funktion [System::MakeObject()](../../system/makeobject/) zugewiesen werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Pointer und verwenden Sie diesen Pointer, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Bitmap : public System::Drawing::Image
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [BeginPixelProcessing](./beginpixelprocessing/)(**bool**) | Aktiviert den Pixelverarbeitungsmodus. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&) | Erzeugt ein neues [Bitmap](./)-Objekt aus dem angegebenen vorhandenen Bild. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**) | Erzeugt ein neues [Bitmap](./)-Objekt aus dem angegebenen Stream. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&) | Erzeugt ein neues [Bitmap](./)-Objekt aus der angegebenen Datei. |
|  [Bitmap](./bitmap/)(const [String](../../system/string/)\&, **bool**) | Erzeugt ein neues [Bitmap](./)-Objekt aus der angegebenen Datei. |
|  [Bitmap](./bitmap/)(int, int, [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Erzeugt ein neues [Bitmap](./)-Objekt, das ein Bitmap-Bild mit der angegebenen Breite, Höhe, Pixelformat und Pixeldaten darstellt. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Size](../size/)\&) | Erzeugt ein neues [Bitmap](./)-Objekt aus dem angegebenen vorhandenen Bild, skaliert auf die angegebene Größe. |
|  [Bitmap](./bitmap/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, int, int) | Erzeugt ein neues [Bitmap](./)-Objekt aus dem angegebenen vorhandenen Bild, dessen Breite und Höhe auf die angegebenen Werte skaliert wurden. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [Clone](./clone/)() override | Erstellt eine Kopie des aktuellen Objekts. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([Rectangle](../rectangle/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Erstellt ein [Bitmap](./)-Objekt, das eine Kopie eines Bereichs des vom aktuellen Objekt dargestellten Bitmap-Bildes darstellt. |
| [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [Clone](./clone/)([RectangleF](../rectanglef/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Erstellt ein [Bitmap](./)-Objekt, das eine Kopie eines Bereichs des vom aktuellen Objekt dargestellten Bitmap-Bildes darstellt. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [ComputeHash](./computehash/)() | Berechnet den SHA1-Hashwert. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [ConvertToARGBImage](./converttoargbimage/)(const [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\>\&) | Erstellt eine Kopie des angegebenen Bitmap-Bildes, wobei das Pixelformat zu Format32bppArgb geändert wird. |
| void [Dispose](../image/dispose/)() override | Gibt alle vom aktuellen Objekt erworbenen Ressourcen frei. |
| **bool** [EndPixelProcessing](./endpixelprocessing/)(**bool**) | Deaktiviert den Pixelverarbeitungsmodus. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, wobei zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromFile](../image/fromfile/)(const [String](../../system/string/)\&, **bool**) | Erstellt ein [Image](../image/)-Objekt aus der angegebenen Datei. |
| static [SharedPtr](../../system/sharedptr/)\<[Bitmap](./)\> [FromHbitmap](../image/fromhbitmap/)(IntPtr) | Erzeugt ein [Bitmap](./)-Objekt aus dem angegebenen GDI-Bitmap. |
| static [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [FromStream](../image/fromstream/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, **bool**, **bool**) | Erstellt ein [Image](../image/)-Objekt aus dem angegebenen Stream. |
| virtual **int32_t** [get_Flags](../image/get_flags/)() const | Gibt eine bitweise Kombination der ImageFlags-Enum-Werte zurück, die die Attribute des Bildes darstellen. |
| [ArrayPtr](../../system/arrayptr/)\<[Guid](../../system/guid/)\> [get_FrameDimensionsList](../image/get_framedimensionslist/)() const | Gibt ein Array von GUIDs zurück, das die Dimensionen der Frames im vom aktuellen Objekt dargestellten Bild repräsentiert. |
| int [get_Height](./get_height/)() const override | Gibt die Höhe des Bildes in Pixeln zurück. |
| **float** [get_HorizontalResolution](../image/get_horizontalresolution/)() const | Gibt die horizontale Auflösung des vom aktuellen Objekt dargestellten Bildes in Pixel pro Zoll zurück. |
| [Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/) [get_Palette](./get_palette/)() const override | Gibt die vom aktuellen Objekt verwendete Farbpalette zurück. |
| [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/) [get_PixelFormat](./get_pixelformat/)() const override | Gibt das Pixelformat des vom aktuellen Objekt dargestellten Bildes zurück. |
| virtual [ArrayPtr](../../system/arrayptr/)\<int\> [get_PropertyIdList](../image/get_propertyidlist/)() const | Ermittelt die IDs der in diesem Bild gespeicherten Property-Items. |
| virtual [ArrayPtr](../../system/arrayptr/)\<[SharedPtr](../../system/sharedptr/)\<[Imaging::PropertyItem](../../system.drawing.imaging/propertyitem/)\>\> [get_PropertyItems](../image/get_propertyitems/)() const | Ermittelt alle Property-Items (Metadaten-Stücke), die in diesem Bild gespeichert sind. |
| [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/) [get_RawFormat](./get_rawformat/)() const override | Gibt das Dateiformat des vom aktuellen Objekt dargestellten Bildes zurück. |
| [Size](../size/) [get_Size](../image/get_size/)() const | Gibt ein [Size](../size/)-Objekt zurück, das die Breite und Höhe des Bildes in Pixeln darstellt. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Tag](../image/get_tag/)() const | Ermittelt ein Objekt, das zusätzliche Daten über das Bild bereitstellt. |
| **float** [get_VerticalResolution](../image/get_verticalresolution/)() const | Gibt die vertikale Auflösung des vom aktuellen Objekt dargestellten Bildes in Pixel pro Zoll zurück. |
| int [get_Width](./get_width/)() const override | Gibt die Breite des Bildes in Pixeln zurück. |
| [RectangleF](../rectanglef/) [GetBounds](../image/getbounds/)([GraphicsUnit](../graphicsunit/)\&) | Gibt die Bildgrenzen in den angegebenen Maßeinheiten zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| int [GetFrameCount](../image/getframecount/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&) | Gibt die Anzahl der Frames der angegebenen Frame-Dimension zurück. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| IntPtr [GetHbitmap](./gethbitmap/)() | Erstellt ein GDI-Bitmap-Objekt aus dem vom aktuellen Objekt dargestellten Bitmap. |
| [Color](../color/) [GetPixel](./getpixel/)(int, int) | Gibt die Farbe des angegebenen Pixels zurück. |
| static int [GetPixelFormatSize](../image/getpixelformatsize/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Gibt die Anzahl der Bits zurück, die zur Darstellung der Farbtiefe im angegebenen Pixelformat verwendet werden. |
| const SkBitmap * [GetSkBitmap](./getskbitmap/)() const override | Gibt einen rohen Zeiger auf das zugrunde liegende SkBitmap-Objekt zurück. |
| [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\> [GetThumbnailImage](../image/getthumbnailimage/)(int, int, [Image::GetThumbnailImageAbort](../image/getthumbnailimageabort/), IntPtr) | Ermittelt ein Thumbnail für dieses [System::Drawing::Image](../image/)-Objekt. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| static **bool** [IsAlphaPixelFormat](../image/isalphapixelformat/)([Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Bestimmt, ob das angegebene Pixelformat Alphainformationen enthält. |
| **bool** [IsMultiImage](./ismultiimage/)() const override | Gibt zurück, ob das Originalformat ein Multi-Image ist. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/)) | Lockt ein [Bitmap](./) in den Systemspeicher. |
| [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/) [LockBits](./lockbits/)(const [Rectangle](../rectangle/)\&, [Imaging::ImageLockMode](../../system.drawing.imaging/imagelockmode/), [Imaging::PixelFormat](../../system.drawing.imaging/pixelformat/), const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Lockt ein [Bitmap](./) in den Systemspeicher. |
| void [MakeTransparent](./maketransparent/)([Color](../color/)) | Ändert die Farbe aller Pixel mit der angegebenen Farbe zu transparent. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
| [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| void [PremultipleColors](./premultiplecolors/)() | Vermultipliziert die Farben der Pixel des vom aktuellen Objekt dargestellten Bildes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [RotateFlip](./rotateflip/)([RotateFlipType](../rotatefliptype/)) override | Dreht das Bild um ein Vielfaches von 90 Grad und spiegelt es. |
| void [Save](../image/save/)(const [String](../../system/string/)\&) | Speichert das vom aktuellen Objekt dargestellte Bild in die angegebene Datei im PNG-Format. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Speichert das vom aktuellen Objekt dargestellte Bild in die angegebene Datei im angegebenen Format. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageFormatPtr](../../system.drawing.imaging/imageformatptr/)\&) | Speichert das vom aktuellen Objekt dargestellte Bild in den angegebenen Stream im angegebenen Format. |
| void [Save](../image/save/)(const [String](../../system/string/)\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Speichert das vom aktuellen Objekt dargestellte Bild in die angegebene Datei unter Verwendung des angegebenen Encoders und der Encoder-Parameter. |
| void [Save](../image/save/)(const [SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>\&, const [Imaging::ImageCodecInfoPtr](../../system.drawing.imaging/imagecodecinfoptr/)\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Speichert das vom aktuellen Objekt dargestellte Bild in den angegebenen Stream unter Verwendung des angegebenen Encoders und der Encoder-Parameter. |
| void [SaveAdd](../image/saveadd/)(const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Fügt einen Frame zur Datei oder zum Stream hinzu, die in einem vorherigen Aufruf der [Save()](../image/save/)-Methode angegeben wurden. |
| void [SaveAdd](../image/saveadd/)(const [SharedPtr](../../system/sharedptr/)\<[Image](../image/)\>\&, const [Imaging::EncoderParametersPtr](../../system.drawing.imaging/encoderparametersptr/)\&) | Fügt einen Frame zur Datei oder zum Stream hinzu, die in einem vorherigen Aufruf der [Save()](../image/save/)-Methode angegeben wurden. |
| int [SelectActiveFrame](../image/selectactiveframe/)(const [Imaging::FrameDimensionPtr](../../system.drawing.imaging/framedimensionptr/)\&, int) | Wählt den angegebenen Frame aus. |
| void [set_Palette](./set_palette/)([Imaging::ColorPalettePtr](../../system.drawing.imaging/colorpaletteptr/)) override | Setzt die vom aktuellen Objekt verwendete Farbpalette. |
| virtual void [set_Tag](../image/set_tag/)(const [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | Setzt ein Objekt, das zusätzliche Daten über das Bild bereitstellt. |
| void [SetPixel](./setpixel/)(int, int, [Color](../color/)) | Setzt die Farbe des angegebenen Pixels im Bitmap-Bild des aktuellen Objekts. |
| void [SetResolution](./setresolution/)(**float**, **float**) | Setzt die Auflösung des Bildes. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument zu einem Weak-Pointer (statt Shared). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den gemeinsamen Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert den C#-typeof([System.Object](../../system/object/))-Konstruktor. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| void [UnlockBits](./unlockbits/)(const [Imaging::BitmapDataPtr](../../system.drawing.imaging/bitmapdataptr/)\&) | Entsperrt das angegebene Bitmap aus dem Systemspeicher. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Image](../image/)
* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)