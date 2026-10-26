---
title: ConvertFromString()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit une chaîne en objet.
type: docs
weight: 40
url: /fr/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) méthode

Convertit une chaîne en objet.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Valeur à convertir. |

### Valeur de retour

objet converti.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) méthode

Convertit une chaîne en objet.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) information de contexte de conversion. |
| text | const [System::String](../../../system/string/)\& | Valeur à convertir. |

### Valeur de retour

objet converti.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) méthode

Convertit une chaîne en objet.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) information de contexte de conversion. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser lors de la conversion d'objets. |
| text | const [System::String](../../../system/string/)\& | Valeur à convertir. |

### Valeur de retour

objet converti.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [TypeConverter](../)
* Classe [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Espace de noms [System::ComponentModel](../../)
* Bibliothèque [Aspose.Slides](../../../)