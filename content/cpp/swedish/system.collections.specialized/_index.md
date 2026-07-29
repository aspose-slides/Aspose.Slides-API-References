---
title: "System::Collections::Specialized"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 391
url: /sv/system.collections.specialized/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BitVector32](./bitvector32/) | Tillhandahåller en enkel lätt bitvektor med enkel heltals- eller [Boolean](../system/boolean/)-åtkomst till en 32 bit lagring. |
| [NameValueCollection](./namevaluecollection/) | Samling av associerade [String](../system/string/)-nycklar och [String](../system/string/)-värden som kan nås antingen med nyckeln eller med indexet. |
| [StringCollection](./stringcollection/) | Indexerad lista av strängar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Wrappa alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |
| [StringCollectionPtr](./stringcollectionptr/) | Strängsamling pekare med åtkomstoperator. |
| [StringDictionary](./stringdictionary/) | [String](../system/string/) till string-ordbok. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i körfel och/eller assertionsfel. Wrappa alltid denna klass i en [System::SmartPtr](../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument. |

## Funktioner

| Funktion | Beskrivning |
| --- | --- |
| **bool** [operator==](./operator_equal_equal/)(**BitVector32::Section**, **BitVector32::Section**) | Kontrollerar om två angivna objekt är lika. |
| **bool** [operator!=](./operator_not_equal/)(**BitVector32::Section**, **BitVector32::Section**) | Kontrollerar om två angivna objekt inte är lika. |