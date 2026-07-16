---
title: StringWriter()
second_title: Référence API Aspose.Slides pour C++
description: Construit une nouvelle instance de StringWriter en utilisant le StringBuilder et IFormatProvider spécifiés.
type: docs
weight: 1
url: /fr/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) constructeur


Construit une nouvelle instance de [StringWriter](../) en utilisant le StringBuilder spécifié et [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | L'objet StringBuilder à utiliser par le [StringWriter](../) en cours de construction |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Un objet [IFormatProvider](../../../system/iformatprovider/) à utiliser par l'objet en cours de construction |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) constructeur


Construit une nouvelle instance de [StringWriter](../) en utilisant le StringBuilder spécifié et [IFormatProvider](../../../system/iformatprovider/) de la culture actuelle.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | L'objet StringBuilder à utiliser par le [StringWriter](../) en cours de construction |

## StringWriter::StringWriter(const IFormatProviderPtr\&) constructeur


Construit une nouvelle instance de [StringWriter](../) en utilisant le [IFormatProvider](../../../system/iformatprovider/) spécifié.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Un objet [IFormatProvider](../../../system/iformatprovider/) à utiliser par l'objet en cours de construction |

## StringWriter::StringWriter() constructeur


Construit une nouvelle instance de [StringWriter](../) en utilisant [IFormatProvider](../../../system/iformatprovider/) de la culture actuelle.

```cpp
System::IO::StringWriter::StringWriter()
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Classe [StringWriter](../)
* Espace de noms [System::IO](../../)
* Bibliothèque [Aspose.Slides](../../../)