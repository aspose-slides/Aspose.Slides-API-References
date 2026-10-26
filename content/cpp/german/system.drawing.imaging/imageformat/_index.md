---
title: ImageFormat
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt das Dateiformat eines Bildes dar. Objekte dieser Klasse sollten ausschließlich mit der System::MakeObject()-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Verpacken Sie diese Klasse stets in einen System::SmartPtr-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 131
url: /de/system.drawing.imaging/imageformat/
---
## ImageFormat Klasse

Stellt das Dateiformat eines Bildes dar. Objekte dieser Klasse sollten ausschließlich mithilfe der [System::MakeObject()](../../system/makeobject/)-Funktion alloziert werden. Erstellen Sie niemals eine Instanz dieses Typs auf dem Stack oder über den Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Verpacken Sie diese Klasse stets in einen [System::SmartPtr](../../system/smartptr/)-Zeiger und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class ImageFormat : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Bestimmt, ob die von dem aktuellen und dem angegebenen Objekt dargestellten Bildformate gleich sind. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN nicht gleich einem Wert ist, einschließlich NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Gleitkommavergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN nicht gleich einem Wert ist, einschließlich NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das Bitmap-Bildformat darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das erweiterte Metadateiformat darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das Exchangeable [Image](../../system.drawing/image/) File (Exif)-Format darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das [Graphics](../../system.drawing/graphics/) Interchange Format (GIF)-Bildformat darstellt. |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Gibt die mit dem Bildformat, das vom aktuellen Objekt dargestellt wird, verbundene GUID zurück. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das [Windows](../../system.windows/)-Icon-Bildformat darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das Joint Photographic Experts Group (JPEG)-Bildformat darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das Format eines Bitmaps im Speicher darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG)-Bildformat darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das Tagged [Image](../../system.drawing/image/) File Format (TIFF)-Bildformat darstellt. |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | Gibt einen gemeinsamen Zeiger auf ein [ImageFormat](./)-Objekt zurück, das das [Windows](../../system.windows/) Metadatei (WMF)-Bildformat darstellt. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ruft die mit dem Objekt verbundene Referenzzähler-Datenstruktur ab. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | Konstruiert eine Instanz der [ImageFormat](./)-Klasse, die ein Bildformat darstellt, das mit der angegebenen GUID verknüpft ist. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte per Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen weak pointer (statt shared). Ermöglicht das Umstellen von Zeigern in Containern auf den weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert die gemeinsame Referenzzählung und gibt sie zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Konvertiert dieses [ImageFormat](./)-Objekt in eine menschenlesbare Zeichenkette. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C#-lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die weak-Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing::Imaging](../)
* Bibliothek [Aspose.Slides](../../)