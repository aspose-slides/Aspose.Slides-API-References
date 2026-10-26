---
title: Point
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt einen Animationspunkt dar.
type: docs
weight: 495
url: /de/aspose.slides.animation/point/
---
## Point Klasse

Stellt einen Animationspunkt dar.

```cpp
class Point : public Aspose::Slides::Animation::IPoint
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte unter Verwendung der C# [Object.Equals](../../system/object/equals/)-Semantik. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert einen C#-ähnlichen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich betrachtet werden, obwohl nach IEC 60559:1989 NaN zu keinem Wert, einschließlich NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| [System::String](../../system/string/) [get_Formula](./get_formula/)() override | Formeln in den Attributen values, from, to, by können aus folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: \\u2018+\\u2019, \\u2018-\\u2018, \\u2018*\\u2019, \\u2018/\\u2019, \\u2018^\\u2019, \\u2018\\u2019 (mod) Konstanten: \\u2018pi\\u2019 \\u2018e\\u2019 Bedingte Operatoren: \\u2018abs\\u2019, \\u2018min\\u2019, \\u2018max\\u2019, \\u2018?\\u2019 (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: \\u2018sin()\\u2019, \\u2018cos()\\u2019, \\u2018tan()\\u2019, \\u2018asin()\\u2019, \\u2018acos()\\u2019, \\u2018atan()\\u2019 Natürlicher Logarithmus \\u2018ln()\\u2019 Eigenschaftsreferenzen (vom Host unterstützte Eigenschaften) |
| **float** [get_Time](./get_time/)() override | Stellt einen Zeitwert dar. Lese **float**. |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_Value](./get_value/)() override | Stellt einen Punktwert dar. Nur: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. Lese [System::Object](../../system/object/). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Ermittelt die Referenzzähler-Datenstruktur, die mit dem Objekt verknüpft ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C#-Methode [Object.GetHashCode()](../../system/object/gethashcode/). Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C#-Aufruf [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator 'is'. |
| void [Lock](../../system/object/lock/)() | Implementiert die C# lock()-Anweisung zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C#-Methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Ermöglicht das Klonen benutzerdefinierter Typen. |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-Konstruktor. Kopiert nichts, tatsächlich nur ein neues Objekt initialisieren und das Kopieren von Unterklassen ermöglichen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, tatsächlich nur ein neues Objekt initialisieren und das Kopieren von Unterklassen ermöglichen. |
|  [Point](./point/)() | Standardkonstruktor. |
|  [Point](./point/)(**float**, [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>, [System::String](../../system/string/)) | Erstellt einen Animationspunkt mit Zeit, Wert und Formel. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von string und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert den gemeinsamen Referenzzähler um den angegebenen Wert. |
| void [set_Formula](./set_formula/)([System::String](../../system/string/)) override | Formeln in den Attributen values, from, to, by können aus folgenden Bestandteilen bestehen: Standardarithmetische Operatoren: \\u2018+\\u2019, \\u2018-\\u2018, \\u2018*\\u2019, \\u2018/\\u2019, \\u2018^\\u2019, \\u2018\\u2019 (mod) Konstanten: \\u2018pi\\u2019 \\u2018e\\u2019 Bedingte Operatoren: \\u2018abs\\u2019, \\u2018min\\u2019, \\u2018max\\u2019, \\u2018?\\u2019 (if) Vergleichsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische Operatoren: \\u2018sin()\\u2019, \\u2018cos()\\u2019, \\u2018tan()\\u2019, \\u2018asin()\\u2019, \\u2018acos()\\u2019, \\u2018atan()\\u2019 Natürlicher Logarithmus \\u2018ln()\\u2019 Eigenschaftsreferenzen (vom Host unterstützte Eigenschaften) |
| void [set_Time](./set_time/)(**float**) override | Stellt einen Zeitwert dar. Schreibe **float**. |
| void [set_Value](./set_value/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Stellt einen Punktwert dar. Nur: bool, [ColorFormat](../../aspose.slides/colorformat/), float, int, string. Schreibe [System::Object](../../system/object/). |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines geteilten). Ermöglicht das Umschalten von Zeigern in Containern auf den schwachen Modus. |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht den gemeinsamen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt den gemeinsamen Referenzzähler zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C#-Methode [Object.ToString()](../../system/object/tostring/). Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementiert die C# lock()-Anweisung zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert den schwachen Referenzzähler. Sollte nicht direkt aufgerufen werden; stattdessen Smart Pointers oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Siehe auch

* Klasse [IPoint](../ipoint/)
* Namensraum [Aspose::Slides::Animation](../)
* Bibliothek [Aspose.Slides](../../)