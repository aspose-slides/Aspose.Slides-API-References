---
title: FontFallBackRule
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Font-Fallback-Regel dar
type: docs
weight: 937
url: /de/aspose.slides/fontfallbackrule/
---
## FontFallBackRule Klasse


Stellt eine Font-Fallback-Regel dar

```cpp
class FontFallBackRule : public Aspose::Slides::IFontFallBackRule
```

## Methoden

| Method | Description |
| --- | --- |
| void [AddFallBackFonts](./addfallbackfonts/)([System::String](../../system/string/)) override | Fügt ein(e) neue(s) Schriftart(en) zur Liste der FallBack-Schriften hinzu. |
| void [AddFallBackFonts](./addfallbackfonts/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | Fügt ein(e) neue Schriftarten zur Liste der FallBack-Schriften hinzu. |
| void [Clear](./clear/)() override | Entfernt alle Schriftarten aus der Liste. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte mit C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-stiligen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-stiligen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::String](../../system/string/)) | Erstellt eine neue Instanz. |
|  [FontFallBackRule](./fontfallbackrule/)(**uint32_t**, **uint32_t**, [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | Erstellt eine neue Instanz. |
| **int32_t** [get_Count](./get_count/)() override | Ermittelt die tatsächliche Anzahl der für den Bereich definierten Schriftarten. Nur lesend **int32_t**. |
| **uint32_t** [get_RangeEndIndex](./get_rangeendindex/)() override | Ermittelt den letzten Index des kontinuierlichen Unicode-Bereichs. |
| **uint32_t** [get_RangeStartIndex](./get_rangestartindex/)() override | Ermittelt den ersten Index des kontinuierlichen Unicode-Bereichs. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die dem Objekt zugeordnet ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| [System::String](../../system/string/) [idx_get](./idx_get/)(**int32_t**) override | Ermittelt den Schriftartnamen am angegebenen Index. Nur lesend [IFontFallBackRule](../ifontfallbackrule/). |
| **int32_t** [IndexOf](./indexof/)([System::String](../../system/string/)) override | Gibt einen Index der angegebenen Regel in der Sammlung zurück. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-'is'-Operator. |
| void [Lock](../../system/object/lock/)() | Implementiert das Sperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt das Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert lediglich ein neues Objekt und ermöglicht das Kopieren von Unterklassen. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht Referenzweise einen Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| void [Remove](./remove/)([System::String](../../system/string/)) override | Entfernt das erste Vorkommen einer bestimmten FallBack-Schriftart aus der Liste. |
| void [RemoveAt](./removeat/)(**int32_t**) override | Entfernt die FallBack-Schriftart am angegebenen Index der Liste. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die geteilte Referenzzählung um den angegebenen Wert. |
| void [set_RangeEndIndex](./set_rangeendindex/)(**uint32_t**) | Ermittelt den letzten Index des kontinuierlichen Unicode-Bereichs. |
| void [set_RangeStartIndex](./set_rangestartindex/)(**uint32_t**) | Ermittelt den ersten Index des kontinuierlichen Unicode-Bereichs. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern in den Weak-Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des geteilten Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die geteilte Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die geteilte Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)() override | Erstellt und gibt ein Array mit allen FallBack-Schriften für diese Regel zurück. |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [ToArray](./toarray/)(**int32_t**, **int32_t**) override | Erstellt und gibt ein Array mit allen FallBack-Schriften aus dem angegebenen Bereich der Liste zurück. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Umwandlung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C# typeof([System.Object](../../system/object/))-Konstrukt. |
| void [Unlock](../../system/object/unlock/)() | Implementiert das Entsperren der C# lock()-Anweisung. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IFontFallBackRule](../ifontfallbackrule/)
* Namensraum [Aspose::Slides](../)
* Bibliothek [Aspose.Slides](../../)