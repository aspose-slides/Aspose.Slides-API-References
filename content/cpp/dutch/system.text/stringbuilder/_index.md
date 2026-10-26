---
title: StringBuilder
second_title: Aspose.Slides voor C++ API-referentie
description: "Buffer om strings deel voor deel te accumuleren. Dit type kan zowel op de stack als value type worden gealloceerd, of op de heap via de System::MakeObject() functie. Zodra het object is gealloceerd, meng deze twee gebruikssituaties nooit: het hebben van SmartPtr pointers naar stack-gealloceerde objecten is strikt verboden."
type: docs
weight: 326
url: /nl/system.text/stringbuilder/
---
## StringBuilder klasse

[Buffer](../../system/buffer/) om strings stap voor stap te accumuleren. Dit type kan zowel op de stack als value type worden gealloceerd, of op de heap via de [System::MakeObject()](../../system/makeobject/) functie. Zodra het object is gealloceerd, meng deze twee gebruikssituaties nooit: het hebben van [SmartPtr](../../system/smartptr/) pointers naar stack-gealloceerde objecten is strikt verboden.

```cpp
class StringBuilder : public System::Object
```

## Methoden

| Method | Description |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Voegt een teken toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Voegt tekens toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Voegt een tekenreeks-array toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Voegt een slice van een tekenreeks-array toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Voegt een string toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Voegt een slice van een string toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Voegt de stringrepresentatie van een object toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Voegt de inhoud van een builder toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Voegt een zwevend-kommagetal toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Voegt een double-waarde toe aan de builder. |
| [StringBuilder](./) * [Append](./append/)(int) | Voegt een geheel getal toe aan de builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Voegt een rekenkundige waarde toe aan de builder. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Voegt de stringrepresentatie van een enum-waarde toe aan de builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Voegt een geformatteerde string toe aan de builder. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Voegt een geformatteerde string toe aan de builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Voegt een nieuweregelteken toe aan de builder. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Voegt een string gevolgd door een nieuweregelteken toe aan de builder. |
| [StringBuilder](./) * [Clear](./clear/)() | Verwijdert alle tekens uit de builder. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Kopieert de data van de builder naar bestaande arrayposities. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Zorgt ervoor dat de capaciteit van deze instantie van [System.Text.StringBuilder](./) ten minste de opgegeven waarde is. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Vergelijkt objecten met C# [Object.Equals](../../system/object/equals/) semantiek. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt referentie-typen objecten in C# stijl. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Vergelijkt waarde-typen objecten in C# stijl. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emuleert een C#-achtige vergelijking van zwevend-kommagetallen waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emuleert een C#-achtige vergelijking van double-waarden waarbij twee NaN’s als gelijk worden beschouwd, hoewel volgens IEC 60559:1989 NaN niet gelijk is aan een waarde, inclusief NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Alleen voor intern gebruik. |
| int [get_Capacity](./get_capacity/)() const | Haalt de huidige capaciteit van de string builder op. |
| int [get_Length](./get_length/)() const | Haalt de huidige lengte van de string in de builder op. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Haalt de referentieteller datastructuur op die met het object geassocieerd is. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analoog aan C# [Object.GetHashCode()](../../system/object/gethashcode/)-methode. Maakt hashing van aangepaste objecten mogelijk. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Haalt het daadwerkelijke type van het object op. Analoge aan C# [System.Object.GetType()](../../system/object/gettype/)-oproep. |
| char_t [idx_get](./idx_get/)(int) const | Haalt het teken op op de opgegeven positie. |
| void [idx_set](./idx_set/)(int, char_t) | Stelt het teken in op de opgegeven positie. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Voegt een string in op een vaste positie in de builder. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Voegt een herhaalde string in op een vaste positie in de builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Voegt een teken in op een vaste positie in de builder. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Voegt tekens in op een vaste positie in de builder. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Voegt een waarde in op een vaste positie in de builder. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Controleert of het object een instantie is van het type dat door targetType wordt beschreven. Analoge aan C# ‘is’-operator. |
| void [Lock](../../system/object/lock/)() | Implementeert C# lock()-statement locking. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analoge aan C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/)-methode. Maakt klonen van aangepaste types mogelijk. |
|  [Object](../../system/object/object/)() | Creëert object. Initialiseert alle interne datastructuren. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Copy-constructor. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subclasses mogelijk. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Assignment-operator. Kopieert niets echt, initialiseert alleen een nieuw object en maakt copy-constructie van subclasses mogelijk. |
| char_t [operator[]](./operator[]/)(int) const | Haalt het teken op op de opgegeven positie. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Vergelijkt objecten per referentie. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Vergelijkt een waarde-type object met nullptr op referentie. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval string en nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisatie van [Object::ReferenceEquals](../../system/object/referenceequals/) voor het geval strings. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Verwijdert fragment uit de builder. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Verlaagt de gedeelde referentieteller met de opgegeven waarde. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Vervangt een substring in de builder. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Vervangt een substring binnen het bereik van de builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Vervangt een teken in de builder. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Vervangt een teken binnen het bereik van de builder. |
| void [set_Capacity](./set_capacity/)(int) | Stelt de huidige capaciteit van de string builder in. |
| void [set_Length](./set_length/)(int) | Kort de string builder af of breidt deze uit tot de opgegeven lengte. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Stelt het n'th-template-argument in op een weak pointer (in plaats van shared). Maakt het mogelijk om pointers in containers naar weak-modus te schakelen. |
| int [SharedCount](../../system/object/sharedcount/)() const | Haalt de huidige waarde van de gedeelde referentieteller op. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Verhoogt de gedeelde referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Verlaagt de gedeelde referentieteller en geeft deze terug. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Constructor. |
|  [StringBuilder](./stringbuilder/)(int) | Constructor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Constructor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Constructor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Constructor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Haalt de huidige string op die in de builder zit. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Haalt het huidige substring op dat in de builder zit. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementeert C# typeof([System.Object](../../system/object/))-construct. |
| void [Unlock](../../system/object/unlock/)() | Implementeert C# lock()-statement unlocking. Roep direct aan of gebruik [LockContext](../../system/lockcontext/)-bewakingsobject. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Verhoogt de weak-referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Verlaagt de weak-referentieteller. Mag niet rechtstreeks worden aangeroepen; gebruik in plaats daarvan smart pointers of ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Vernietigt object. Vrijt alle interne datastructuren. |
|  [~StringBuilder](./~stringbuilder/)() | Destructor. |
## Zie ook

* Class [Object](../../system/object/)
* Namespace [System::Text](../)
* Library [Aspose.Slides](../../)