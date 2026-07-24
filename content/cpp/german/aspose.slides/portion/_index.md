---
title: Portion
second_title: Aspose.Slides für C++ API Referenz
description: Stellt einen Teil des Textes innerhalb eines Textabsatzes dar.
type: docs
weight: 4772
url: /de/aspose.slides/portion/
---
## Portion Klasse

Stellt einen Teil des Textes innerhalb eines Textabsatzes dar.

```cpp
class Portion : public Aspose::Slides::IPortion,
                public Aspose::Slides::IDOMObject
```

## Methoden

| Method | Description |
| --- | --- |
| void [AddField](./addfield/)([System::SharedPtr](../../system/sharedptr/)\<[IFieldType](../ifieldtype/)\>) override | Konvertiert diesen Abschnitt in das automatisch aktualisierte Feld. |
| void [AddField](./addfield/)([System::String](../../system/string/)) override | Konvertiert diesen Abschnitt in das automatisch aktualisierte Feld. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich betrachtet werden, obwohl NaN gemäß IEC 60559:1989 zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::SharedPtr](../../system/sharedptr/)\<[IField](../ifield/)\> [get_Field](./get_field/)() override | Gibt ein Feld dieses Abschnitts zurück. Nur-Lesen [IField](../ifield/). |
| [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_PortionFormat](./get_portionformat/)() override | Gibt ein Formatierungsobjekt zurück, das explizit gesetzte Formatierungseigenschaften des Textabschnitts enthält, ohne dass Vererbung angewendet wird. Nur-Lesen [IPortionFormat](../iportionformat/). |
| [System::String](../../system/string/) [get_Text](./get_text/)() override | Liest den Klartext eines Abschnitts. Lesen [System::String](../../system/string/). |
| [System::Drawing::PointF](../../system.drawing/pointf/) [GetCoordinates](./getcoordinates/)() override | Ermittelt die Koordinaten des Beginns des Abschnitts. Die X-Koordinate des Punktes repräsentiert den Abschnittsbeginn ab dem ersten Zeichen inklusive des linken Side-Bearings. Die Y-Koordinate beinhaltet das obere Side-Bearing. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetRect](./getrect/)() override | Ermittelt die Koordinaten des Rechtecks, das den Abschnitt begrenzt. Das Rechteck umfasst alle Textzeilen im Abschnitt, einschließlich leerer Zeilen. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert die Sperrung des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstruieren von Unterklassen. |
|  [Portion](./portion/)() | Initialisiert eine neue Instanz der [Portion](./)-Klasse. |
|  [Portion](./portion/)([System::String](../../system/string/)) | Initialisiert eine neue Instanz der [Portion](./)-Klasse. |
|  [Portion](./portion/)([System::SharedPtr](../../system/sharedptr/)\<[Portion](./)\>) | Initialisiert eine neue Instanz der [Portion](./)-Klasse. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht ein Werttyp-Objekt per Referenz mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den Shared-Referenzzähler um den angegebenen Wert. |
| void [RemoveField](./removefield/)() override | Konvertiert diesen Feldabschnitt in den einfachen Abschnitt. |
| void [set_Text](./set_text/)([System::String](../../system/string/)) override | Setzt den Klartext eines Abschnitts. Schreiben [System::String](../../system/string/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines Shared-Zeigers). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des Shared-Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den Shared-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert den Shared-Referenzzähler und gibt ihn zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren des C# lock()-Statements. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den Weak-Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IPortion](../iportion/)
* Klasse [IDOMObject](../idomobject/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)