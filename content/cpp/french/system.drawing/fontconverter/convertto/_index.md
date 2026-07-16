---
title: ConvertTo()
second_title: Aspose.Slides pour C++ Référence de l'API
description: Convertit l'objet vers un type spécifique.
type: docs
weight: 14
url: /fr/system.drawing/fontconverter/convertto/
---
## FontConverter::ConvertTo(const System::SharedPtr\<ComponentModel::ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Convertit l'objet vers un type spécifique.

```cpp
System::SharedPtr<System::Object> System::Drawing::FontConverter::ConvertTo(const System::SharedPtr<ComponentModel::ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType) override
```


### Paramètres

| Parameter | Type | Description |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ComponentModel::ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informations de contexte de conversion. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Culture à utiliser lors de la conversion des objets. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | Un objet à convertir. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Type vers lequel convertir. |

### Valeur de retour

Objet converti.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [ITypeDescriptorContext](../../../system.componentmodel/itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [FontConverter](../)
* Espace de noms [System::Drawing](../../)
* Bibliothèque [Aspose.Slides](../../../)