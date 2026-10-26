---
title: "System::Text::RegularExpressions"
second_title: Aspose.Slides C++ API referenciája
description: 
type: docs
weight: 989
url: /hu/system.text.regularexpressions/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [Capture](./capture/) | Egyetlen al-kifejezés illesztésének eredménye. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
| [CaptureCollection](./capturecollection/) | Az egyetlen capture csoport által végrehajtott capture-ek listája. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
| [Group](./group/) | Az egyetlen capture csoport által végrehajtott illesztés eredménye. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
| [GroupCollection](./groupcollection/) | Egyetlen egyezés során a capture csoportok listája. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
| [GroupCollectionPtr](./groupcollectionptr/) | [Group](./group/) gyűjtemény mutató. Ez a típus egy mutató, amely más objektumok törlését kezeli. A veremben kell allokálni, és átadni a függvényeknek értékként vagy const referenciaként. |
| [Match](./match/) | [Single](../system/single/) reguláris kifejezés (regexp) illesztése a stringen. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
| [MatchCollection](./matchcollection/) | A reguláris kifejezést (regexp) többszöri alkalmazásával a stringen végrehajtott illesztések gyűjteménye. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
| [Regex](./regex/) | C#-hoz hasonló szintaxist használó reguláris kifejezés. Az osztály objektumait csak a [System::MakeObject()](../system/makeobject/) függvénnyel szabad allokálni. Soha ne hozzon létre példányt ebből a típusból a veremben vagy az new operátorral, mert futásidejű hibákat és/vagy állítási hibákat okoz. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) mutatóba, és használja ezt a mutatót az osztály argumentumként való átadásához a függvényeknek. |
## Függvények

| Függvény | Leírás |
| --- | --- |
| [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Wrapper a MatchHolder osztály megtartásához anélkül, hogy be lenne szerelve, valamint a PCRE2-hez. |
## Enumerációk

| Enum | Leírás |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) opciók. |
## Typedefek

| Typedef | Leírás |
| --- | --- |
| [UStringPtr](./ustringptr/) | Megosztott UnicodeString a másolás elkerülésére. |
| [CapturePtr](./captureptr/) | Mutató egyetlen capture objektumra. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Mutató capture gyűjteményre. |
| [GroupPtr](./groupptr/) | Mutató csoportra. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) mutató. |
| [MatchPtr](./matchptr/) | [Match](./match/) mutató. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) gyűjtemény mutató. |
| [MatchEvaluator](./matchevaluator/) | Delegált típus az illesztés kiértékeléséhez. |