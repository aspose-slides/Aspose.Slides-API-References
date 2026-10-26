---
title: IParagraphFormat
second_title: Aspose.Slides für C++ API-Referenz
description: Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu IParagraphFormatEffectiveData sind alle Eigenschaften dieser Klasse schreibbar.
type: docs
weight: 3147
url: /de/aspose.slides/iparagraphformat/
---
## IParagraphFormat Klasse


Diese Klasse enthält die Absatzformatierungseigenschaften. Im Gegensatz zu [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/) sind alle Eigenschaften dieser Klasse schreibbar.

```cpp
class IParagraphFormat : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-artigen Gleitkomma-Vergleich, bei dem zwei NaNs als gleich angesehen werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [TextAlignment](../textalignment/) [get_Alignment](./get_alignment/)() | Gibt die Textausrichtung in einem Absatz ohne Vererbung zurück. Lesen [TextAlignment](../textalignment/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBulletFormat](../ibulletformat/)\> [get_Bullet](./get_bullet/)() | Gibt das Aufzählungsformat des Absatzes zurück. Nur-Lesen [IBulletFormat](../ibulletformat/). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPortionFormat](../iportionformat/)\> [get_DefaultPortionFormat](./get_defaultportionformat/)() | Gibt das Standard-Abschnittsformat eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [IPortionFormat](../iportionformat/). |
| virtual **float** [get_DefaultTabSize](./get_defaulttabsize/)() | Gibt die Standard-Tabulationsgröße ohne Vererbung zurück. Lesen **float**. |
| virtual **int16_t** [get_Depth](./get_depth/)() | Gibt die Tiefe des Absatzes zurück. Der Wert 0 bedeutet einen undefinierten Wert. Lesen **int16_t**. |
| virtual [NullableBool](../nullablebool/) [get_EastAsianLineBreak](./get_eastasianlinebreak/)() | Bestimmt, ob der Ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| virtual [Aspose::Slides::FontAlignment](../fontalignment/) [get_FontAlignment](./get_fontalignment/)() | Gibt eine Schriftartausrichtung in einem Absatz ohne Vererbung zurück. Lesen [Slides::FontAlignment](../fontalignment/). |
| virtual [NullableBool](../nullablebool/) [get_HangingPunctuation](./get_hangingpunctuation/)() | Bestimmt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| virtual **float** [get_Indent](./get_indent/)() | Gibt den Erstzeileneinzug/den hängenden Einzug des Absatzes ohne Vererbung zurück. Der hängende Einzug kann mit negativen Werten definiert werden. Lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_LatinLineBreak](./get_latinlinebreak/)() | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| virtual **float** [get_MarginLeft](./get_marginleft/)() | Gibt den linken Rand in einem Absatz ohne Vererbung zurück. Lesen **float**. |
| virtual **float** [get_MarginRight](./get_marginright/)() | Gibt den rechten Rand in einem Absatz ohne Vererbung zurück. Lesen **float**. |
| virtual [NullableBool](../nullablebool/) [get_RightToLeft](./get_righttoleft/)() | Bestimmt, ob die Rechts-zu-Links-Schrift in einem Absatz verwendet wird. Keine Vererbung angewendet. Lesen [NullableBool](../nullablebool/). |
| virtual **float** [get_SpaceAfter](./get_spaceafter/)() | Gibt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung zurück. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen **float**. |
| virtual **float** [get_SpaceBefore](./get_spacebefore/)() | Gibt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung zurück. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Lesen **float**. |
| virtual **float** [get_SpaceWithin](./get_spacewithin/)() | Gibt den Abstand zwischen Grundlinien in einem Absatz zurück. Positiver Wert bedeutet Prozentsatz, negativer – Größe in Punkten. Keine Vererbung angewendet. Lesen **float**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITab](../itab/)\> [get_Tab](./get_tab/)(**int32_t**) | Gibt die Tabulation eines Absatzes am angegebenen Index zurück. Keine Vererbung angewendet. Nur-Lesen [Aspose::Slides::ITab](../itab/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITabCollection](../itabcollection/)\> [get_Tabs](./get_tabs/)() | Gibt die Tabulationen eines Absatzes zurück. Keine Vererbung angewendet. Nur-Lesen [ITabCollection](../itabcollection/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)\> [GetEffective](./geteffective/)() | Ermittelt die effektiven Absatzformatierungsdaten mit angewandter Vererbung. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-„is“-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das C# lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert tatsächlich nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| virtual void [set_Alignment](./set_alignment/)([TextAlignment](../textalignment/)) | Setzt die Textausrichtung in einem Absatz ohne Vererbung. Schreiben [TextAlignment](../textalignment/). |
| virtual void [set_DefaultTabSize](./set_defaulttabsize/)(**float**) | Setzt die Standard-Tabulationsgröße ohne Vererbung. Schreiben **float**. |
| virtual void [set_Depth](./set_depth/)(**int16_t**) | Setzt die Tiefe des Absatzes. Der Wert 0 bedeutet einen undefinierten Wert. Schreiben **int16_t**. |
| virtual void [set_EastAsianLineBreak](./set_eastasianlinebreak/)([NullableBool](../nullablebool/)) | Bestimmt, ob der Ostasiatische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_FontAlignment](./set_fontalignment/)([Aspose::Slides::FontAlignment](../fontalignment/)) | Setzt eine Schriftartausrichtung in einem Absatz ohne Vererbung. Schreiben [Slides::FontAlignment](../fontalignment/). |
| virtual void [set_HangingPunctuation](./set_hangingpunctuation/)([NullableBool](../nullablebool/)) | Bestimmt, ob hängende Interpunktion in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_Indent](./set_indent/)(**float**) | Setzt den Erstzeileneinzug/den hängenden Einzug des Absatzes ohne Vererbung. Der hängende Einzug kann mit negativen Werten definiert werden. Schreiben **float**. |
| virtual void [set_LatinLineBreak](./set_latinlinebreak/)([NullableBool](../nullablebool/)) | Bestimmt, ob der lateinische Zeilenumbruch in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_MarginLeft](./set_marginleft/)(**float**) | Setzt den linken Rand in einem Absatz ohne Vererbung. Schreiben **float**. |
| virtual void [set_MarginRight](./set_marginright/)(**float**) | Setzt den rechten Rand in einem Absatz ohne Vererbung. Schreiben **float**. |
| virtual void [set_RightToLeft](./set_righttoleft/)([NullableBool](../nullablebool/)) | Bestimmt, ob die Rechts-zu-Links-Schrift in einem Absatz verwendet wird. Keine Vererbung angewendet. Schreiben [NullableBool](../nullablebool/). |
| virtual void [set_SpaceAfter](./set_spaceafter/)(**float**) | Setzt den Abstand nach der letzten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Schreiben **float**. |
| virtual void [set_SpaceBefore](./set_spacebefore/)(**float**) | Setzt den Abstand vor der ersten Zeile in einem Absatz ohne Vererbung. Ein positiver Wert gibt den Prozentsatz der Schriftgröße an, den der Leerraum einnehmen soll. Ein negativer Wert gibt die Größe des Leerraums in Punktgröße an. Schreiben **float**. |
| virtual void [set_SpaceWithin](./set_spacewithin/)(**float**) | Setzt den Abstand zwischen Grundlinien in einem Absatz. Positiver Wert bedeutet Prozentsatz, negativer – Größe in Punkten. Keine Vererbung angewendet. Schreiben **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht das Konvertieren benutzerdefinierter Objekte zu einem String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C# lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Bemerkungen

Diese Klasse wird verwendet, um die für den jeweiligen Absatz definierten Absatzformatierungseigenschaften zurückzugeben und zu manipulieren. Das bedeutet, dass beim Abfragen von Werten keine Vererbung angewendet wird, sodass in den meisten Fällen Werte zurückgegeben werden, die „undefiniert“ bedeuten.

Um die effektiven Formatierungsparameterwerte einschließlich vererbter Werte zu erhalten, müssen Sie die [IParagraphFormat::GetEffective](./geteffective/)-Methode verwenden, die eine [IParagraphFormatEffectiveData](../iparagraphformateffectivedata/)-Instanz zurückgibt.

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)