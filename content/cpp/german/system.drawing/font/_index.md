---
title: Font
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt ein bestimmtes Textformat dar, einschließlich Schriftart, Größe und Stil. Objekte dieser Klasse sollten nur mit der System::MakeObject()-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen System::SmartPtr-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben."
type: docs
weight: 79
url: /de/system.drawing/font/
---
## Font Klasse

Representiert ein bestimmtes Textformat, einschließlich Schriftart, Größe und Stil. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../../system/makeobject/)-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs auf dem Stack oder mit dem Operator new, da dies zu Laufzeitfehlern und/oder Assertionsfehlern führt. Wickeln Sie diese Klasse immer in einen [System::SmartPtr](../../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben.

```cpp
class Font : public System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [Clone](./clone/)() | Gibt eine Kopie des aktuellen Font zurück. |
| void [Dispose](./dispose/)() | Gibt alle vom aktuellen Objekt erworbenen Betriebssystem-Ressourcen frei. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Bestimmt, ob das aktuelle und das angegebene Objekt identisch sind. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit der C# [Object.Equals](../../system/object/equals/) Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[Font](./)\>\&, [FontStyle](../fontstyle/)) | Konstruiert eine neue Instanz der Klasse [Font](./), die die angegebene vorhandene Schrift mit dem angegebenen Schriftsstil darstellt. |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Konstruiert eine neue Instanz der Klasse [Font](./). |
|  [Font](./font/)(const [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\>\&, **float**, [GraphicsUnit](../graphicsunit/)) | Konstruiert eine neue Instanz der Klasse [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [FontStyle](../fontstyle/), [GraphicsUnit](../graphicsunit/), **uint8_t**, **bool**) | Konstruiert eine neue Instanz der Klasse [Font](./). |
|  [Font](./font/)(const [String](../../system/string/)\&, **float**, [GraphicsUnit](../graphicsunit/)) | Konstruiert eine neue Instanz der Klasse [Font](./). |
| static [SharedPtr](../../system/sharedptr/)\<[Font](./)\> [FromLogFont](./fromlogfont/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | NICHT IMPLEMENTIERT. |
| **bool** [get_Bold](./get_bold/)() | Bestimmt, ob der vom aktuellen Objekt dargestellte Font den Fettdruckstil angewendet hat. |
| [SharedPtr](../../system/sharedptr/)\<[FontFamily](../fontfamily/)\> [get_FontFamily](./get_fontfamily/)() | Gibt die Schriftfamilie des vom aktuellen Objekt dargestellten Font zurück. |
| [FontStyle](../fontstyle/) [get_FontStyle](./get_fontstyle/)() | Gibt den Schriftsstil des vom aktuellen Objekt dargestellten Font zurück. |
| **uint8_t** [get_GdiCharSet](./get_gdicharset/)() | Gibt einen Wert zurück, der den von der vom aktuellen Objekt dargestellten Schrift verwendeten GDI-Zeichensatz angibt. |
| int [get_Height](./get_height/)() | Gibt den Zeilenabstand der vom aktuellen Objekt dargestellten Schrift in Pixeln zurück. |
| **bool** [get_Italic](./get_italic/)() | Bestimmt, ob der vom aktuellen Objekt dargestellte Font den Kursivstil angewendet hat. |
| [String](../../system/string/) [get_Name](./get_name/)() | Gibt den Namen der Schriftart der vom aktuellen Objekt dargestellten Schrift zurück. |
| [String](../../system/string/) [get_OriginalFontName](./get_originalfontname/)() | Gibt den ursprünglich angegebenen Namen der Schrift zurück. |
| **float** [get_Size](./get_size/)() | Gibt die Em-Größe der vom aktuellen Objekt dargestellten Schrift zurück, gemessen in den durch die Eigenschaft Unit angegebenen Einheiten. |
| **float** [get_SizeInPoints](./get_sizeinpoints/)() | Gibt die Em-Größe der vom aktuellen Objekt dargestellten Schrift in Punkten zurück. |
| **bool** [get_Strikeout](./get_strikeout/)() | Bestimmt, ob der vom aktuellen Objekt dargestellte Font den Durchstreichstil angewendet hat. |
| [FontStyle](../fontstyle/) [get_Style](./get_style/)() | Gibt den Schriftsstil des vom aktuellen Objekt dargestellten Font zurück. |
| **bool** [get_Underline](./get_underline/)() | Bestimmt, ob der vom aktuellen Objekt dargestellte Font den Unterstreichstil angewendet hat. |
| [GraphicsUnit](../graphicsunit/) [get_Unit](./get_unit/)() | Gibt die Maßeinheit für die vom aktuellen Objekt dargestellte Schrift zurück. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| **float** [GetHeight](./getheight/)(const [SharedPtr](../../system/sharedptr/)\<[Graphics](../graphics/)\>\&) | Gibt den Zeilenabstand der vom aktuellen Objekt dargestellten Schrift zurück, in der aktuellen Einheit eines angegebenen [Graphics](../graphics/)-Objekts. |
| **float** [GetHeight](./getheight/)(**float**) | Gibt die Höhe der vom aktuellen Objekt dargestellten Schrift zurück, wenn sie auf einem Anzeigegerät mit der angegebenen vertikalen Auflösung gezeichnet wird. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Überprüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-‘is’-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruktion von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in Zeichenketten. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen sollten intelligente Zeiger oder ThisProtector verwendet werden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [System::Drawing](../)
* Bibliothek [Aspose.Slides](../../)