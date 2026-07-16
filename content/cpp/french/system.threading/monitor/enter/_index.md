---
title: Enter()
second_title: Référence API Aspose.Slides pour C++
description: Acquiert un verrou exclusif sur un objet spécifié.
type: docs
weight: 1
url: /fr/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) méthode


Acquiert un verrou exclusif sur un objet spécifié.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'objet sur lequel acquérir le verrou du moniteur. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) méthode


Acquiert un verrou exclusif sur l'objet spécifié et définit de manière atomique une valeur indiquant si le verrou a été pris.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Espace de noms [System::Threading](../../)
* Bibliothèque [Aspose.Slides](../../../)