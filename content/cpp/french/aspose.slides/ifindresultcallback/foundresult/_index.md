---
title: FoundResult()
second_title: Référence de l'API Aspose.Slides pour C++
description: Méthode de rappel qui reçoit les données concernant le texte trouvé.
type: docs
weight: 1
url: /fr/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) méthode

Méthode de rappel qui reçoit les données concernant le texte trouvé.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Le [ITextFrame](../../itextframe/) dans lequel le texte a été trouvé. |
| sourceText | [System::String](../../../system/string/) | Le texte source dans lequel le texte a été trouvé. |
| foundText | [System::String](../../../system/string/) | Le texte trouvé. |
| textPosition | **int32_t** | La position du texte trouvé. |

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)