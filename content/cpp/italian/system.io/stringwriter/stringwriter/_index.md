---
title: StringWriter()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza di StringWriter utilizzando lo StringBuilder specificato e IFormatProvider.
type: docs
weight: 1
url: /it/system.io/stringwriter/stringwriter/
---
## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&, const IFormatProviderPtr\&) costruttore

Crea una nuova istanza di [StringWriter](../) utilizzando lo StringBuilder specificato e [IFormatProvider](../../../system/iformatprovider/).

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb, const IFormatProviderPtr &formatProvider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | L'oggetto StringBuilder da utilizzare dal [StringWriter](../) in costruzione |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Un oggetto [IFormatProvider](../../../system/iformatprovider/) da utilizzare dall'oggetto in costruzione |

## StringWriter::StringWriter(const System::SharedPtr\<Text::StringBuilder\>\&) costruttore

Crea una nuova istanza di [StringWriter](../) utilizzando lo StringBuilder specificato e [IFormatProvider](../../../system/iformatprovider/) dalla cultura corrente.

```cpp
System::IO::StringWriter::StringWriter(const System::SharedPtr<Text::StringBuilder> &sb)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sb | const [System::SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | L'oggetto StringBuilder da utilizzare dal [StringWriter](../) in costruzione |

## StringWriter::StringWriter(const IFormatProviderPtr\&) costruttore

Crea una nuova istanza di [StringWriter](../) utilizzando il [IFormatProvider](../../../system/iformatprovider/) specificato.

```cpp
System::IO::StringWriter::StringWriter(const IFormatProviderPtr &formatProvider)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formatProvider | const [IFormatProviderPtr](../../../system/iformatproviderptr/)\& | Un oggetto [IFormatProvider](../../../system/iformatprovider/) da utilizzare dall'oggetto in costruzione |

## StringWriter::StringWriter() costruttore

Crea una nuova istanza di [StringWriter](../) utilizzando [IFormatProvider](../../../system/iformatprovider/) dalla cultura corrente.

```cpp
System::IO::StringWriter::StringWriter()
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [IFormatProviderPtr](../../../system/iformatproviderptr/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Classe [StringWriter](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)