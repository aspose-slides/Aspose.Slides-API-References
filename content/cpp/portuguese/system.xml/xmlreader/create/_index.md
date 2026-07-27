---
title: Create()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova instância XmlReader com o URI especificado.
type: docs
weight: 1015
url: /pt/system.xml/xmlreader/create/
---
## XmlReader::Create(const String\&) método

Cria uma nova instância [XmlReader](../) com o URI especificado.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI para o arquivo que contém os dados XML. A classe [XmlUrlResolver](../../xmlurlresolver/) é usada para converter o caminho em uma representação de dados canônica. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const String\&, const SharedPtr\<XmlReaderSettings\>\&) método

Cria uma nova instância [XmlReader](../) usando o URI e as configurações especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI para o arquivo que contém os dados XML. O objeto [XmlResolver](../../xmlresolver/) no objeto [XmlReaderSettings](../../xmlreadersettings/) é usado para converter o caminho em uma representação de dados canônica. Se o valor de XmlReaderSettings::get_XmlResolver for **nullptr**, um novo objeto [XmlUrlResolver](../../xmlurlresolver/) é usado. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const String\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) método

Cria uma nova instância [XmlReader](../) usando o URI, as configurações e as informações de contexto de análise especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const String &inputUri, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| inputUri | const [String](../../../system/string/)\& | O URI para o arquivo que contém os dados XML. O objeto [XmlResolver](../../xmlresolver/) no objeto [XmlReaderSettings](../../xmlreadersettings/) é usado para converter o caminho em uma representação de dados canônica. Se o valor de XmlReaderSettings::get_XmlResolver for **nullptr**, um novo objeto [XmlUrlResolver](../../xmlurlresolver/) é usado. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | As informações de contexto necessárias para analisar o fragmento XML. As informações de contexto podem incluir o [XmlNameTable](../../xmlnametable/) a ser usado, codificação, escopo de namespace, o escopo atual de **xml:lang** e **xml:space**, URI base e definição de tipo de documento. Este valor pode ser **nullptr**. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&) método

Cria uma nova instância [XmlReader](../) usando o fluxo especificado com as configurações padrão.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo que contém os dados XML. O [XmlReader](../) analisa os primeiros bytes do fluxo em busca de uma marca de ordem de bytes ou outro sinal de codificação. Quando a codificação é determinada, ela é usada para continuar a leitura do fluxo, e o processamento continua analisando a entrada como um fluxo de caracteres (Unicode). |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<XmlReaderSettings\>\&) método

Cria uma nova instância [XmlReader](../) com o fluxo e as configurações especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo que contém os dados XML. O [XmlReader](../) analisa os primeiros bytes do fluxo em busca de uma marca de ordem de bytes ou outro sinal de codificação. Quando a codificação é determinada, ela é usada para continuar a leitura do fluxo, e o processamento continua analisando a entrada como um fluxo de caracteres (Unicode). |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) método

Cria uma nova instância [XmlReader](../) usando o fluxo, o URI base e as configurações especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo que contém os dados XML. O [XmlReader](../) analisa os primeiros bytes do fluxo em busca de uma marca de ordem de bytes ou outro sinal de codificação. Quando a codificação é determinada, ela é usada para continuar a leitura do fluxo, e o processamento continua analisando a entrada como um fluxo de caracteres (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | O URI base para a entidade ou documento sendo lido. Este valor pode ser **nullptr**. **[Security](../../../system.security/) Nota** O URI base é usado para resolver o URI relativo do documento XML. Não use um URI base de uma fonte não confiável. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::Stream\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) método

Cria uma nova instância [XmlReader](../) usando o fluxo, as configurações e as informações de contexto de análise especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::Stream> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | O fluxo que contém os dados XML. O [XmlReader](../) analisa os primeiros bytes do fluxo em busca de uma marca de ordem de bytes ou outro sinal de codificação. Quando a codificação é determinada, ela é usada para continuar a leitura do fluxo, e o processamento continua analisando a entrada como um fluxo de caracteres (Unicode). |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | As informações de contexto necessárias para analisar o fragmento XML. As informações de contexto podem incluir o [XmlNameTable](../../xmlnametable/) a ser usado, codificação, escopo de namespace, o escopo atual de **xml:lang** e **xml:space**, URI base e definição de tipo de documento. Este valor pode ser **nullptr**. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&) método

Cria uma nova instância [XmlReader](../) usando o leitor de texto especificado.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O leitor de texto a partir do qual ler os dados XML. Um leitor de texto retorna um fluxo de caracteres Unicode, portanto a codificação especificada na declaração XML não é usada pelo leitor XML para decodificar o fluxo de dados. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, const SharedPtr\<XmlReaderSettings\>\&) método

Cria uma nova instância [XmlReader](../) usando o leitor de texto e as configurações especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, const SharedPtr<XmlReaderSettings> &settings)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O leitor de texto a partir do qual ler os dados XML. Um leitor de texto retorna um fluxo de caracteres Unicode, portanto a codificação especificada na declaração XML não é usada pelo leitor XML para decodificar o fluxo de dados. |
| settings | const [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\>\& | As configurações para o novo [XmlReader](../). Este valor pode ser **nullptr**. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const String\&) método

Cria uma nova instância [XmlReader](../) usando o leitor de texto, as configurações e o URI base especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const String &baseUri)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O leitor de texto a partir do qual ler os dados XML. Um leitor de texto retorna um fluxo de caracteres Unicode, portanto a codificação especificada na declaração XML não é usada pelo [XmlReader](../) para decodificar o fluxo de dados. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |
| baseUri | const [String](../../../system/string/)\& | O URI base para a entidade ou documento sendo lido. Este valor pode ser **nullptr**. **[Security](../../../system.security/) Nota** O URI base é usado para resolver o URI relativo do documento XML. Não use um URI base de uma fonte não confiável. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<IO::TextReader\>\&, SharedPtr\<XmlReaderSettings\>, const SharedPtr\<XmlParserContext\>\&) método

Cria uma nova instância [XmlReader](../) usando o leitor de texto, as configurações e as informações de contexto de análise especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<IO::TextReader> &input, SharedPtr<XmlReaderSettings> settings, const SharedPtr<XmlParserContext> &inputContext)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [SharedPtr](../../../system/sharedptr/)\<[IO::TextReader](../../../system.io/textreader/)\>\& | O leitor de texto a partir do qual ler os dados XML. Um leitor de texto retorna um fluxo de caracteres Unicode, portanto a codificação especificada na declaração XML não é usada pelo leitor XML para decodificar o fluxo de dados. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | As configurações para a nova instância [XmlReader](../). Este valor pode ser **nullptr**. |
| inputContext | const [SharedPtr](../../../system/sharedptr/)\<[XmlParserContext](../../xmlparsercontext/)\>\& | As informações de contexto necessárias para analisar o fragmento XML. As informações de contexto podem incluir o [XmlNameTable](../../xmlnametable/) a ser usado, codificação, escopo de namespace, o escopo atual de **xml:lang** e **xml:space**, URI base e definição de tipo de documento. Este valor pode ser **nullptr**. |

### Valor de Retorno

Um objeto usado para ler os dados XML no fluxo.

## XmlReader::Create(const SharedPtr\<XmlReader\>\&, SharedPtr\<XmlReaderSettings\>) método

Cria uma nova instância [XmlReader](../) usando o leitor XML e as configurações especificados.

```cpp
static SharedPtr<XmlReader> System::Xml::XmlReader::Create(const SharedPtr<XmlReader> &reader, SharedPtr<XmlReaderSettings> settings)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| reader | const [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../)\>\& | O objeto que você deseja usar como o leitor XML subjacente. |
| settings | [SharedPtr](../../../system/sharedptr/)\<[XmlReaderSettings](../../xmlreadersettings/)\> | As configurações para a nova instância [XmlReader](../). O nível de conformidade do objeto [XmlReaderSettings](../../xmlreadersettings/) deve coincidir com o nível de conformidade do leitor subjacente, ou deve ser definido como [ConformanceLevel::Auto](../../conformancelevel/). |

### Valor de Retorno

Um objeto que envolve o objeto [XmlReader](../) especificado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../)
* Classe [String](../../../system/string/)
* Classe [XmlReaderSettings](../../xmlreadersettings/)
* Classe [XmlParserContext](../../xmlparsercontext/)
* Classe [Stream](../../../system.io/stream/)
* Classe [TextReader](../../../system.io/textreader/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)