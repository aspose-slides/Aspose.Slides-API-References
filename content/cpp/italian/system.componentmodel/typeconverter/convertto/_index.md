---
title: ConvertTo()
second_title: Riferimento API Aspose.Slides per C++
description: Converte l'oggetto a un tipo specifico.
type: docs
weight: 53
url: /it/system.componentmodel/typeconverter/convertto/
---
## TypeConverter::ConvertTo(const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converte l'oggetto a un tipo specifico.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) da convertire. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Tipo a cui convertire. |

### Valore restituito

Oggetto convertito.

## TypeConverter::ConvertTo(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::SharedPtr\<System::Object\>\&, const System::TypeInfo\&) method


Converte l'oggetto a un tipo specifico.

```cpp
virtual System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertTo(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::SharedPtr<System::Object> &value, const System::TypeInfo &destinationType)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informazioni sul contesto di conversione. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da utilizzare durante la conversione degli oggetti. |
| value | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\>\& | [Object](../../../system/object/) da convertire. |
| destinationType | const [System::TypeInfo](../../../system/typeinfo/)\& | Tipo a cui convertire. |

### Valore restituito

Oggetto convertito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [TypeInfo](../../../system/typeinfo/)
* Classe [TypeConverter](../)
* Classe [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System::ComponentModel](../../)
* Libreria [Aspose.Slides](../../../)