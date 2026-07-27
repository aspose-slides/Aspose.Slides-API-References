---
title: StringWriter()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância de StringWriter usando o StringBuilder especificado e IFormatProvider.
type: docs
weight: 1
url: /pt/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) construtor


Constrói uma nova instância de [StringWriter](../) usando o StringBuilder especificado e [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | O objeto StringBuilder a ser usado pelo [StringWriter](../) que está sendo construído |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Um objeto [IFormatProvider](../../../system/iformatprovider/) a ser usado pelo objeto que está sendo construído |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) construtor


Constrói uma nova instância de [StringWriter](../) usando o StringBuilder especificado e [IFormatProvider](../../../system/iformatprovider/) da cultura atual.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | O objeto StringBuilder a ser usado pelo [StringWriter](../) que está sendo construído |

## StringWriter::StringWriter(const IFormatProviderPtr\&) construtor


Constrói uma nova instância de [StringWriter](../) usando o [IFormatProvider](../../../system/iformatprovider/) especificado.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Um objeto [IFormatProvider](../../../system/iformatprovider/) a ser usado pelo objeto que está sendo construído |

## StringWriter::StringWriter() construtor


Constrói uma nova instância de [StringWriter](../) usando [IFormatProvider](../../../system/iformatprovider/) da cultura atual.

```cpp
System::IO::StringWriter::StringWriter()
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Class [StringBuilder](../../../system.text/stringbuilder/)
* Class [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)