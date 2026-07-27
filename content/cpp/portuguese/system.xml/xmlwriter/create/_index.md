---
title: Create()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova instância de XmlWriter usando o nome de arquivo especificado.
type: docs
weight: 469
url: /pt/system.xml/xmlwriter/create/
---
## XmlWriter::Create(const String\&) method

Cria uma nova instância [XmlWriter](../) usando o nome de arquivo especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | O arquivo no qual você deseja gravar. O [XmlWriter](../) cria um arquivo no caminho especificado e grava nele usando a sintaxe de texto XML 1.0. O **outputFileName** deve ser um caminho de sistema de arquivos. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const String\&, SharedPtr\<XmlWriterSettings\>) method

Cria uma nova instância [XmlWriter](../) usando o nome de arquivo e o objeto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const String &outputFileName, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFileName | const [String](../../../system/string/)\& | O arquivo no qual você deseja gravar. O [XmlWriter](../) cria um arquivo no caminho especificado e grava nele usando a sintaxe de texto XML 1.0. O **outputFileName** deve ser um caminho de sistema de arquivos. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | O objeto [XmlWriterSettings](../../xmlwritersettings/) usado para configurar a nova instância [XmlWriter](../). Se for **nullptr**, um [XmlWriterSettings](../../xmlwritersettings/) com configurações padrão será usado. Se o [XmlWriter](../) estiver sendo usado com o método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), você deve usar o valor XslCompiledTransform::get_OutputSettings para obter um objeto [XmlWriterSettings](../../xmlwritersettings/) com as configurações corretas. Isso garante que o objeto [XmlWriter](../) criado tenha as configurações de saída corretas. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&) method

Cria uma nova instância [XmlWriter](../) usando o fluxo especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo no qual você deseja gravar. O [XmlWriter](../) grava a sintaxe de texto XML 1.0 e o anexa ao fluxo especificado. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlWriterSettings\>) method

Cria uma nova instância [XmlWriter](../) usando o fluxo e o objeto [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::Stream> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo no qual você deseja gravar. O [XmlWriter](../) grava a sintaxe de texto XML 1.0 e o anexa ao fluxo especificado. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | O objeto [XmlWriterSettings](../../xmlwritersettings/) usado para configurar a nova instância [XmlWriter](../). Se for **nullptr**, um [XmlWriterSettings](../../xmlwritersettings/) com configurações padrão será usado. Se o [XmlWriter](../) estiver sendo usado com o método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), você deve usar o valor XslCompiledTransform::get_OutputSettings para obter um objeto [XmlWriterSettings](../../xmlwritersettings/) com as configurações corretas. Isso garante que o objeto [XmlWriter](../) criado tenha as configurações de saída corretas. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&) method

Cria uma nova instância [XmlWriter](../) usando o TextWriter especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter no qual você deseja gravar. O [XmlWriter](../) grava a sintaxe de texto XML 1.0 e a anexa ao TextWriter especificado. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<IO::TextWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

Cria uma nova instância [XmlWriter](../) usando o TextWriter e os objetos [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<IO::TextWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextWriter](../../../system.io/textwriter/)\>\& | O TextWriter no qual você deseja gravar. O [XmlWriter](../) grava a sintaxe de texto XML 1.0 e a anexa ao TextWriter especificado. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | O objeto [XmlWriterSettings](../../xmlwritersettings/) usado para configurar a nova instância [XmlWriter](../). Se for **nullptr**, um [XmlWriterSettings](../../xmlwritersettings/) com configurações padrão será usado. Se o [XmlWriter](../) estiver sendo usado com o método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), você deve usar o valor XslCompiledTransform::get_OutputSettings para obter um objeto [XmlWriterSettings](../../xmlwritersettings/) com as configurações corretas. Isso garante que o objeto [XmlWriter](../) criado tenha as configurações de saída corretas. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&) method

Cria uma nova instância [XmlWriter](../) usando o [Text::StringBuilder](../../../system.text/stringbuilder/) especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | O [Text::StringBuilder](../../../system.text/stringbuilder/) no qual escrever. O conteúdo gravado pelo [XmlWriter](../) é anexado ao [Text::StringBuilder](../../../system.text/stringbuilder/). |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<Text::StringBuilder\>\&, SharedPtr\<XmlWriterSettings\>) method

Cria uma nova instância [XmlWriter](../) usando os objetos [Text::StringBuilder](../../../system.text/stringbuilder/) e [XmlWriterSettings](../../xmlwritersettings/).

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<Text::StringBuilder> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[Text::StringBuilder](../../../system.text/stringbuilder/)\>\& | O [Text::StringBuilder](../../../system.text/stringbuilder/) no qual escrever. O conteúdo gravado pelo [XmlWriter](../) é anexado ao [Text::StringBuilder](../../../system.text/stringbuilder/). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | O objeto [XmlWriterSettings](../../xmlwritersettings/) usado para configurar a nova instância [XmlWriter](../). Se for **nullptr**, um [XmlWriterSettings](../../xmlwritersettings/) com configurações padrão será usado. Se o [XmlWriter](../) estiver sendo usado com o método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), você deve usar o valor XslCompiledTransform::get_OutputSettings para obter um objeto [XmlWriterSettings](../../xmlwritersettings/) com as configurações corretas. Isso garante que o objeto [XmlWriter](../) criado tenha as configurações de saída corretas. |

### Valor de Retorno

Um objeto [XmlWriter](../).

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&) method

Cria uma nova instância [XmlWriter](../) usando o objeto [XmlWriter](../) especificado.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | O objeto [XmlWriter](../) que você deseja usar como escritor subjacente. |

### Valor de Retorno

Um objeto [XmlWriter](../) que envolve o objeto [XmlWriter](../) especificado.

## XmlWriter::Create(const SharedPtr\<XmlWriter\>\&, SharedPtr\<XmlWriterSettings\>) method

Cria uma nova instância [XmlWriter](../) usando os objetos [XmlWriter](../) e [XmlWriterSettings](../../xmlwritersettings/) especificados.

```cpp
static SharedPtr<XmlWriter> System::Xml::XmlWriter::Create(const SharedPtr<XmlWriter> &output, SharedPtr<XmlWriterSettings> settings)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| output | const [SharedPtr](../../../system/sharedptr/)\<[XmlWriter](../)\>\& | O objeto [XmlWriter](../) que você deseja usar como escritor subjacente. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlWriterSettings](../../xmlwritersettings/)\> | O objeto [XmlWriterSettings](../../xmlwritersettings/) usado para configurar a nova instância [XmlWriter](../). Se for **nullptr**, um [XmlWriterSettings](../../xmlwritersettings/) com configurações padrão será usado. Se o [XmlWriter](../) estiver sendo usado com o método XslCompiledTransform:Transform(String,SharedPtr<XmlWriter>), você deve usar o valor XslCompiledTransform::get_OutputSettings para obter um objeto [XmlWriterSettings](../../xmlwritersettings/) com as configurações corretas. Isso garante que o objeto [XmlWriter](../) criado tenha as configurações de saída corretas. |

### Valor de Retorno

Um objeto [XmlWriter](../) que envolve o objeto [XmlWriter](../) especificado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../)
* Classe [String](../../../system/string/)
* Classe [XmlWriterSettings](../../xmlwritersettings/)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextWriter](../../../system.io/textwriter/)
* Classe [StringBuilder](../../../system.text/stringbuilder/)
* Espaço de nomes [System::Xml](../../)
* Library [Aspose.Slides](../../../)