---
title: GetEnvironmentVariables()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει ένα λεξικό που περιέχει όλα τα ονόματα μεταβλητών περιβάλλοντος και τις τιμές τους που σχετίζονται με τη τρέχουσα διεργασία.
type: docs
weight: 326
url: /el/system/environment/getenvironmentvariables/
---
## Environment::GetEnvironmentVariables() μέθοδος


Επιστρέφει ένα λεξικό που περιέχει όλα τα ονόματα μεταβλητών περιβάλλοντος και τις τιμές τους που σχετίζονται με τη τρέχουσα διαδικασία.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables()
```

## Environment::GetEnvironmentVariables(EnvironmentVariableTarget) μέθοδος


Επιστρέφει ένα λεξικό που περιέχει όλα τα ονόματα των μεταβλητών περιβάλλοντος και τις τιμές τους από την καθορισμένη θέση.

```cpp
static Collections::Generic::DictionaryPtr<String, String> System::Environment::GetEnvironmentVariables(EnvironmentVariableTarget target)
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| target | [EnvironmentVariableTarget](../../environmentvariabletarget/) | Η θέση των μεταβλητών |

### Τιμή Επιστροφής

Ένα λεξικό που περιέχει όλα τα ονόματα των μεταβλητών περιβάλλοντος και τις τιμές τους από την καθορισμένη θέση

## Δείτε επίσης

* Enum [EnvironmentVariableTarget](../../environmentvariabletarget/)
* Κλάση [DictionaryPtr](../../../system.collections.generic/dictionaryptr/)
* Κλάση [String](../../string/)
* Struct [Environment](../)
* ΧώροςΟνομάτων [System](../../)
* Library [Aspose.Slides](../../../)