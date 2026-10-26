---
title: "System::Text::RegularExpressions"
second_title: Référence API Aspose.Slides pour C++
description: 
type: docs
weight: 989
url: /fr/system.text.regularexpressions/
---
## Classes

| Classe | Description |
| --- | --- |
| [Capture](./capture/) | Résultat d’une correspondance d’une sous-expression unique. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
| [CaptureCollection](./capturecollection/) | Liste des captures effectuées par un groupe de capture unique. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
| [Group](./group/) | Résultat d’une correspondance effectuée par un groupe de capture unique. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
| [GroupCollection](./groupcollection/) | Liste des groupes de capture dans une correspondance unique. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
| [GroupCollectionPtr](./groupcollectionptr/) | Pointeur de collection [Group](./group/). Ce type est un pointeur pour gérer la suppression d’un autre objet. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence const. |
| [Match](./match/) | Correspondance [Single](../system/single/) d’une expression régulière sur une chaîne. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
| [MatchCollection](./matchcollection/) | Collection de correspondances obtenues en appliquant de manière répétée une expression régulière à une chaîne. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
| [Regex](./regex/) | Expression régulière qui suit une syntaxe semblable à C#. Les objets de cette classe ne doivent être alloués qu’en utilisant la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d’instance de ce type sur la pile ou en utilisant l’opérateur new, car cela entraînera des erreurs d’exécution et/ou des échecs d’assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu’argument. |
## Fonctions

| Fonction | Description |
| --- | --- |
| [ASPOSECPP_3RD_PARTY_UNCOPYBALE_TYPE_HOLDER](./asposecpp_3rd_party_uncopybale_type_holder/)(Detail::MatchHolder, MatchHolder, sizeof(Detail::DummyMatchHolder), Detail::DummyMatchHolder, MatchHolderAlias) | Enveloppe pour conserver la classe MatchHolder sans son inclusion ainsi que PCRE2. |
## Énumérations

| Énumération | Description |
| --- | --- |
| [RegexOptions](./regexoptions/) | [Regex](./regex/) options. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [UStringPtr](./ustringptr/) | UnicodeString partagé pour éviter les copies. |
| [CapturePtr](./captureptr/) | Pointeur vers un objet de capture unique. |
| [CaptureCollectionPtr](./capturecollectionptr/) | Pointeur vers une collection de captures. |
| [GroupPtr](./groupptr/) | Pointeur vers un groupe. |
| [RegexPtr](./regexptr/) | [Regex](./regex/) pointeur. |
| [MatchPtr](./matchptr/) | [Match](./match/) pointeur. |
| [MatchCollectionPtr](./matchcollectionptr/) | [Match](./match/) pointeur de collection. |
| [MatchEvaluator](./matchevaluator/) | Type delegate pour évaluer la correspondance. |