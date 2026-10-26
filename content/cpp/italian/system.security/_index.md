---
title: "System::Security"
second_title: Riferimento API Aspose.Slides per C++
description: 
type: docs
weight: 807
url: /it/system.security/
---
## Classi

| Classe | Descrizione |
| --- | --- |
| [Details_SecurityException](./details_securityexception/) |  |
| [SecureString](./securestring/) | Stringa sicura, rappresenta testo che deve rimanere confidenziale. Questa classe NON CRIPTA i dati interni. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |
| [SecureStringMarshal](./securestringmarshal/) | Raccolta di metodi per allocare e copiare blocchi di memoria non gestita. |
| [SecurityElement](./securityelement/) | Modello di oggetto XML per la codifica dell'oggetto di sicurezza. Non implementato. Gli oggetti di questa classe dovrebbero essere allocati solo usando la funzione [System::MakeObject()](../system/makeobject/). Non creare mai un'istanza di questo tipo sullo stack o usando l'operatore new, poiché ciò provocherà errori di runtime e/o errori di asserzione. Avvolgi sempre questa classe in un puntatore [System::SmartPtr](../system/smartptr/) e usa questo puntatore per passarla alle funzioni come argomento. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [SecurityException](./securityexception/) |  |
| [SecureStringPtr](./securestringptr/) | [SecureString](./securestring/) tipo puntatore. |