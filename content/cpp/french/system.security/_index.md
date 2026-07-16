---
title: "System::Security"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 807
url: /fr/system.security/
---
## Classes

| Class | Description |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Chaîne sécurisée, représente du texte qui doit rester confidentiel. Cette classe NE CHIFFRE PAS les données internes. Les objets de cette classe doivent uniquement être alloués à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
| [SecureStringMarshal](./securestringmarshal/) | Collection de méthodes pour allouer et copier des blocs de mémoire non gérés. |
| [SecurityElement](./securityelement/) | Modèle d'objet XML pour l'encodage d'un objet de sécurité. Non implémenté. Les objets de cette classe doivent uniquement être alloués à l'aide de la fonction [System::MakeObject()](../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../system/smartptr/) et utilisez ce pointeur pour le transmettre aux fonctions en tant qu'argument. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) type pointeur. |