---
title: ConvertFromString()
second_title: Riferimento API di Aspose.Slides per C++
description: Converte la stringa in un oggetto.
type: docs
weight: 40
url: /it/system.componentmodel/typeconverter/convertfromstring/
---
## TypeConverter::ConvertFromString(const System::String\&) metodo


Converte la stringa in un oggetto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::String &text)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | const [System::String](../../../system/string/)\& | Valore da convertire. |

### Valore restituito

oggetto convertito.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::String\&) metodo


Converte la stringa in un oggetto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::String &text)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informazioni sul contesto di conversione. |
| text | const [System::String](../../../system/string/)\& | Valore da convertire. |

### Valore restituito

oggetto convertito.

## TypeConverter::ConvertFromString(const System::SharedPtr\<ITypeDescriptorContext\>\&, const System::SharedPtr\<System::Globalization::CultureInfo\>\&, const System::String\&) metodo


Converte la stringa in un oggetto.

```cpp
System::SharedPtr<System::Object> System::ComponentModel::TypeConverter::ConvertFromString(const System::SharedPtr<ITypeDescriptorContext> &context, const System::SharedPtr<System::Globalization::CultureInfo> &culture, const System::String &text)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| context | const [System::SharedPtr](../../../system/sharedptr/)\<[ITypeDescriptorContext](../../itypedescriptorcontext/)\>\& | [Object](../../../system/object/) informazioni sul contesto di conversione. |
| culture | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Cultura da usare durante la conversione di oggetti. |
| text | const [System::String](../../../system/string/)\& | Valore da convertire. |

### Valore restituito

oggetto convertito.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [TypeConverter](../)
* Classe [ITypeDescriptorContext](../../itypedescriptorcontext/)
* Classe [CultureInfo](../../../system.globalization/cultureinfo/)
* Spazio dei nomi [System::ComponentModel](../../)
* Libreria [Aspose.Slides](../../../)