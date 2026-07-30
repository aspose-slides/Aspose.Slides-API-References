---
title: GetObjectStoringLocation()
second_title: Riferimento API Aspose.Slides per C++
description: Determina dove l'oggetto dovrebbe essere memorizzato. Questo metodo viene chiamato una volta per ogni ID dell'oggetto. Non è garantito che non esistano due oggetti con gli stessi dati, semanticName e contentType ma con ID diverso.
type: docs
weight: 1
url: /it/aspose.slides.export/ilinkembedcontroller/getobjectstoringlocation/
---
## ILinkEmbedController::GetObjectStoringLocation(int32_t, System::ArrayPtr\<uint8_t\>, System::String, System::String, System::String) metodo

Determina dove l'oggetto dovrebbe essere memorizzato. Questo metodo viene chiamato una volta per ogni ID dell'oggetto. Non è garantito che non esistano due oggetti con gli stessi dati, semanticName e contentType ma con ID diverso.

```cpp
virtual LinkEmbedDecision Aspose::Slides::Export::ILinkEmbedController::GetObjectStoringLocation(int32_t id, System::ArrayPtr<uint8_t> entityData, System::String semanticName, System::String contentType, System::String recomendedExtension)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| id | **int32_t** | ID dell'oggetto. Questo ID è univoco per l'intera operazione di salvataggio. |
| entityData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Dati binari dell'oggetto. Questo parametro può essere nullo, se i dati binari dell'oggetto non sono ancora generati. |
| semanticName | [System::String](../../../system/string/) | Qualche breve testo, che descrive il significato dell'oggetto. Il controller può usarlo come parte del nome esterno dell'oggetto, ma spetta al dispatcher garantire che i nomi siano unici e contengano solo i caratteri consentiti. |
| contentType | [System::String](../../../system/string/) | Tipo MIME dell'oggetto. |
| recomendedExtension | [System::String](../../../system/string/) | Estensione del nome file, raccomandata per questo tipo MIME. |

### Valore di ritorno

Decision

## Vedi anche

* Enum [LinkEmbedDecision](../../linkembeddecision/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [ILinkEmbedController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)