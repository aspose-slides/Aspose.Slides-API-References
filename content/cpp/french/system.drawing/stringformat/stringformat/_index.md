---
title: StringFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: "Construit une nouvelle instance de la classe StringFormat."
type: docs
weight: 1
url: /fr/system.drawing/stringformat/stringformat/
---
## StringFormat::StringFormat() constructeur

Construit une nouvelle instance de [StringFormat](../) class.

```cpp
System::Drawing::StringFormat::StringFormat()
```

## StringFormat::StringFormat(StringFormatFlags, int32_t) constructeur

Construit une nouvelle instance de [StringFormat](../) class avec les indicateurs de format spécifiés et la langue.

```cpp
System::Drawing::StringFormat::StringFormat(StringFormatFlags options, int32_t language=0)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| options | [StringFormatFlags](../../stringformatflags/) | Une combinaison bit à bit de la valeur d'énumération StringFormatFlags qui spécifie le format de chaîne à représenter par l'objet créé |
| language | **int32_t** | La langue du texte |

## StringFormat::StringFormat(const SharedPtr\<StringFormat\>\&) constructeur

Constructeur de copie.

```cpp
System::Drawing::StringFormat::StringFormat(const SharedPtr<StringFormat> &format)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| format | const [SharedPtr](../../../system/sharedptr/)\<[StringFormat](../)\>\& | Un objet [StringFormat](../) à copier |

## Voir aussi

* Enum [StringFormatFlags](../../stringformatflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StringFormat](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)