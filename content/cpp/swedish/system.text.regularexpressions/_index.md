---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 989
url: /sv/system.text.regularexpressions/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [Capture](./capture/) | Resultat av en enskild deluttrycksmatchning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [CaptureCollection](./capturecollection/) | Lista över fångster utförda av en enskild fångstgrupp. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Group](./group/) | Resultat av matchning utförd av en enskild fångstgrupp. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [GroupCollection](./groupcollection/) | Lista över fångstgrupper i en enskild matchning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) samlingspekare. Denna typ är en pekare för att hantera borttagning av andra objekt. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens. |
| [Match](./match/) | [Single](../system/single/) matchning av reguljärt uttryck över en sträng. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [MatchCollection](./matchcollection/) | Samling av matchningar utförda genom att upprepade gånger applicera reguljärt uttryck på en sträng. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
| [Regex](./regex/) | Reguljärt uttryck som följer C#-liknande syntax. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att resultera i runtime-fel och/eller assertion-fel. Wrappa alltid den här klassen i en [System::SmartPtr](../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument. |
## Funktioner

| Funktion | Beskrivning |
| --- | --- |
|  [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Wrapper för att hålla MatchHolder-klassen utan dess inkludering samt PCRE2. |
## Enum

| Enum | Beskrivning |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) alternativ. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [UStringPtr](./ustringptr/) | Delad UnicodeString för att undvika kopiering. |
| [CapturePtr](./captureptr/) | Pekare till ett enskilt fångstobjekt. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Pekare till en fångstsamling. |
| [GroupPtr](./groupptr/) | Pekare till grupp. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) pekare. |
| [MatchPtr](./matchptr/) | [Match](./match/) pekare. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) samlingspekare. |
| [MatchEvaluator](./matchevaluator/) | Delegattyp för att utvärdera matchning. |