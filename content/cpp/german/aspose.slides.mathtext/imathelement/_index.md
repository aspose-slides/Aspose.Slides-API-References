---
title: IMathElement
second_title: Aspose.Slides für C++ API-Referenz
description: "Basis-Interface jedes mathematischen Elements: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw."
type: docs
weight: 222
url: /de/aspose.slides.mathtext/imathelement/
---
## IMathElement Klasse

Basis-Interface jedes mathematischen Elements: Bruch, mathematischer Text, Funktion, Ausdruck mit mehreren Elementen usw.

```cpp
class IMathElement : public virtual System::Object
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathAccent](../imathaccent/)\> [Accent](./accent/)(char16_t) | Setzt ein Akzentzeichen (ein Zeichen oben auf diesem Element) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([System::String](../../system/string/)) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfOneArgument](../mathfunctionsofoneargument/)) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient, und einen zusätzlichen angegebenen Parameter |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [AsArgumentOfFunction](./asargumentoffunction/)([MathFunctionsOfTwoArguments](../mathfunctionsoftwoarguments/), [System::String](../../system/string/)) | Verwendet die angegebene Funktion, wobei diese Instanz als Argument dient, und einen zusätzlichen angegebenen Parameter |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::String](../../system/string/)) | Erstellt einen Bruch mit diesem Zähler und dem angegebenen Nenner |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [MathFractionTypes](../mathfractiontypes/)) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFraction](../imathfraction/)\> [Divide](./divide/)([System::String](../../system/string/), [MathFractionTypes](../mathfractiontypes/)) | Erstellt einen Bruch des angegebenen Typs mit diesem Zähler und dem angegebenen Nenner |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)() | Umschließt ein mathematisches Element in Klammern |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathDelimiter](../imathdelimiter/)\> [Enclose](./enclose/)(char16_t, char16_t) | Umschließt dieses Element in angegebenen Zeichen, wie z. B. Klammern oder anderen Zeichen als Rahmen |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergleicht Objekte nach den C# [Object.Equals](../../system/object/equals/)-Semantiken. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Referenztyp-Objekte im C#-Stil. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergleicht Werttyp-Objekte im C#-Stil. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl NaN nach IEC 60559:1989 zu keinem Wert, auch nicht zu NaN, gleich ist. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuliert den C#-artigen Vergleich von Gleitkommazahlen, bei dem zwei NaNs als gleich gelten, obwohl NaN nach IEC 60559:1989 zu keinem Wert, auch nicht zu NaN, gleich ist. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Nur für interne Zwecke. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](./function/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname dient |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathFunction](../imathfunction/)\> [Function](./function/)([System::String](../../system/string/)) | Verwendet eine Funktion eines Arguments, wobei diese Instanz als Funktionsname dient |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>\> [GetChildren](./getchildren/)() | Gibt Kindelemente zurück |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Liefert die Referenzzähler-Datenstruktur, die mit dem Objekt verbunden ist. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analog zur C# [Object.GetHashCode()](../../system/object/gethashcode/)-Methode. Ermöglicht das Hashen benutzerdefinierter Objekte. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Ermittelt den tatsächlichen Typ des Objekts. Analog zum C# [System.Object.GetType()](../../system/object/gettype/)-Aufruf. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](./group/)() | Platziert dieses Element in einer Gruppe mit einer geschweiften Klammer unten |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathGroupingCharacter](../imathgroupingcharacter/)\> [Group](./group/)(char16_t, [MathTopBotPositions](../mathtopbotpositions/), [MathTopBotPositions](../mathtopbotpositions/)) | Platziert dieses Element in einer Gruppe mit einem Gruppierungszeichen, z. B. einer geschweiften Klammer unten oder einem anderen Zeichen |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [MathLimitLocations](../mathlimitlocations/)) | Berechnet das Integral |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Berechnet das Integral |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/)) | Berechnet das Integral ohne Grenzen |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/), [MathLimitLocations](../mathlimitlocations/)) | Berechnet das Integral |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Integral](./integral/)([MathIntegralTypes](../mathintegraltypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Berechnet das Integral |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Prüft, ob das Objekt eine Instanz des durch targetType beschriebenen Typs darstellt. Analog zum C#-Operator „is“. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](./join/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Verbindet ein mathematisches Element und bildet einen mathematischen Block |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBlock](../imathblock/)\> [Join](./join/)([System::String](../../system/string/)) | Verbindet einen mathematischen Text und bildet einen mathematischen Block |
| void [Lock](../../system/object/lock/)() | Implementiert das C#-lock()-Statement zum Sperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analog zur C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-Methode. Ermöglicht das Klonen benutzerdefinierter Typen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](./nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Erstellt einen n-stelligen Operator |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathNaryOperator](../imathnaryoperator/)\> [Nary](./nary/)([MathNaryOperatorTypes](../mathnaryoperatortypes/), [System::String](../../system/string/), [System::String](../../system/string/)) | Erstellt einen n-stelligen Operator |
|  [Object](../../system/object/object/)() | Erstellt ein Objekt. Initialisiert alle internen Datenstrukturen. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Kopierkonstruktor. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Zuweisungsoperator. Kopiert nichts, sondern initialisiert nur ein neues Objekt und ermöglicht das Kopierkonstrukt von Unterklassen. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Overbar](./overbar/)() | Setzt einen Balken oben auf dieses Element |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](./radical/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRadical](../imathradical/)\> [Radical](./radical/)([System::String](../../system/string/)) | Gibt die mathematische Wurzel des angegebenen Grades aus dem angegebenen Argument an |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergleicht Objekte nach Referenz. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergleicht per Referenz ein Werttyp-Objekt mit nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenkette und nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spezialisierung von [Object::ReferenceEquals](../../system/object/referenceequals/) für den Fall von Zeichenketten. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verringert die gemeinsame Referenzzählung um den angegebenen Wert. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](./setlowerlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Nimmt untere Grenze |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetLowerLimit](./setlowerlimit/)([System::String](../../system/string/)) | Nimmt untere Grenze |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](./setsubscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Erstellt Tiefstellung |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSubscriptElement](../imathsubscriptelement/)\> [SetSubscript](./setsubscript/)([System::String](../../system/string/)) | Erstellt Tiefstellung |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](./setsubsuperscriptontheleft/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Erstellt Tief- und Hochstellung links |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLeftSubSuperscriptElement](../imathleftsubsuperscriptelement/)\> [SetSubSuperscriptOnTheLeft](./setsubsuperscriptontheleft/)([System::String](../../system/string/), [System::String](../../system/string/)) | Erstellt Tief- und Hochstellung links |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](./setsubsuperscriptontheright/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Erstellt Tief- und Hochstellung rechts |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathRightSubSuperscriptElement](../imathrightsubsuperscriptelement/)\> [SetSubSuperscriptOnTheRight](./setsubsuperscriptontheright/)([System::String](../../system/string/), [System::String](../../system/string/)) | Erstellt Tief- und Hochstellung rechts |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](./setsuperscript/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Erstellt Hochstellung |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathSuperscriptElement](../imathsuperscriptelement/)\> [SetSuperscript](./setsuperscript/)([System::String](../../system/string/)) | Erstellt Hochstellung |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Setzt das n-te Template-Argument auf einen schwachen Zeiger (statt eines gemeinsamen). Ermöglicht das Umschalten von Zeigern in Containern auf den Schwachmodus. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](./setupperlimit/)([System::SharedPtr](../../system/sharedptr/)\<[IMathElement](./)\>) | Nimmt obere Grenze |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathLimit](../imathlimit/)\> [SetUpperLimit](./setupperlimit/)([System::String](../../system/string/)) | Nimmt obere Grenze |
| int [SharedCount](../../system/object/sharedcount/)() const | Ermittelt den aktuellen Wert des gemeinsamen Referenzzählers. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Erhöht die gemeinsame Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verringert und gibt die gemeinsame Referenzzählung zurück. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](./toborderbox/)() | Platziert dieses Element in einer Rahmenbox |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBorderBox](../imathborderbox/)\> [ToBorderBox](./toborderbox/)(**bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**, **bool**) | Platziert dieses Element in einer Rahmenbox |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBox](../imathbox/)\> [ToBox](./tobox/)() | Platziert dieses Element in einer nicht-visuellen Box (logische Gruppierung), die verwendet wird, um Komponenten einer Gleichung oder anderer mathematischer Texte zu gruppieren. Ein verpacktes Objekt kann (zum Beispiel) als Operator-Emulator mit oder ohne Ausrichtungspunkt dienen, als Zeilenumbruchpunkt fungieren oder so gruppiert werden, dass kein Zeilenumbruch innerhalb zulässig ist. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathArray](../imatharray/)\> [ToMathArray](./tomatharray/)() | Setzt in ein vertikales Array |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analog zur C# [Object.ToString()](../../system/object/tostring/)-Methode. Ermöglicht die Konvertierung benutzerdefinierter Objekte in einen String. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementiert das C#-Konstrukt typeof([System.Object](../../system/object/)). |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMathBar](../imathbar/)\> [Underbar](./underbar/)() | Setzt einen Balken unten auf dieses Element |
| void [Unlock](../../system/object/unlock/)() | Implementiert das C#-lock()-Statement zum Entsperren. Direkt aufrufen oder das [LockContext](../../system/lockcontext/)-Wächterobjekt verwenden. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Erhöht die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verringert die schwache Referenzzählung. Sollte nicht direkt aufgerufen werden; stattdessen Smart-Pointer oder ThisProtector verwenden. |
| virtual  [~Object](../../system/object/~object/)() | Zerstört das Objekt. Gibt alle internen Datenstrukturen frei. |

## Anmerkungen

Beispiel: 
```cpp
auto element1 = System::MakeObject<MathematicalText>(u"x");
auto element2 = System::MakeObject<MathematicalText>(u"y");
```

## Siehe auch

* Klasse [Object](../../system/object/)
* Namensraum [Aspose::Slides::MathText](../)
* Bibliothek [Aspose.Slides](../../)