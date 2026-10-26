---
title: ResolveUri()
second_title: Référence API Aspose.Slides pour C++
description: Résout l'URI absolu à partir des URI de base et relatifs.
type: docs
weight: 1
url: /fr/aspose.slides.import/iexternalresourceresolver/resolveuri/
---
## IExternalResourceResolver::ResolveUri(System::String, System::String) méthode


Résout l'URI absolu à partir des URI de base et relatifs.

```cpp
virtual System::String Aspose::Slides::Import::IExternalResourceResolver::ResolveUri(System::String baseUri, System::String relativeUri)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseUri | [System::String](../../../system/string/) | URI de base des objets de liaison |
| relativeUri | [System::String](../../../system/string/) | URI relatif vers l'objet lié. |

### Valeur de retour

URI absolu ou null si l'URI relatif ne peut pas être résolu.

## Voir aussi

* Classe [String](../../../system/string/)
* Classe [IExternalResourceResolver](../)
* Espace de noms [Aspose::Slides::Import](../../)
* Bibliothèque [Aspose.Slides](../../../)