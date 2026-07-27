---
title: Guid
second_title: Referência da API Aspose.Slides para C++
description: "Representa um Identificador Globalmente Único. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos deste tipo."
type: docs
weight: 885
url: /pt/system/guid/
---
## Guid classe


Representa um Identificador Globalmente Único. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos deste tipo.

```cpp
class Guid
```

## Métodos

| Method | Description |
| --- | --- |
| int [CompareTo](./compareto/)(const [Guid](./)\&) const | Realiza comparação aritmética dos GUIDs representados pelo objeto atual e pelo objeto especificado. |
| **bool** [Equals](./equals/)(const [Guid](./)\&) const | Determina se os GUIDs representados pelo objeto atual e pelo objeto especificado são iguais. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
|  [Guid](./guid/)() | Constrói um objeto que representa um GUID composto por zeros. |
|  [Guid](./guid/)(const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Constrói um objeto que representa um GUID especificado como um array de valores inteiros sem sinal de 8 bits. |
|  [Guid](./guid/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Constrói um objeto que representa um GUID especificado como uma visualização de array de valores inteiros sem sinal de 8 bits. |
|  [Guid](./guid/)(const [String](../string/)\&) | Constrói um objeto que representa um GUID especificado como uma string. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const [ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | Constrói uma instância da classe [Guid](./) a partir dos componentes GUID especificados. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, const System::Details::ArrayView\<**uint8_t**\>\&) | Constrói uma instância da classe [Guid](./) a partir dos componentes GUID especificados. |
|  [Guid](./guid/)(**int32_t**, **int16_t**, **int16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Constrói uma instância da classe [Guid](./) a partir dos inteiros sem sinal e bytes especificados. |
|  [Guid](./guid/)(**uint32_t**, **uint16_t**, **uint16_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**, **uint8_t**) | Constrói uma instância da classe [Guid](./) a partir dos inteiros sem sinal e bytes especificados. |
|  [Guid](./guid/)(const [Guid](./)\&) | Constrói um objeto que representa o mesmo GUID do objeto especificado. |
| static [Guid](./) [NewGuid](./newguid/)() | Gera um novo GUID e retorna um objeto [Guid](./) que o representa. |
| **bool** [operator!=](./operator_not_equal/)(const [Guid](./)\&) const | Determina se os GUIDs representados pelo objeto atual e pelo objeto especificado não são iguais. |
| [Guid](./)\& [operator=](./operator_equal/)(const [Guid](./)\&) | Atribui ao objeto atual o valor GUID representado pelo objeto [Guid](./) especificado. |
| **bool** [operator==](./operator_equal_equal/)(const [Guid](./)\&) const | Determina se os GUIDs representados pelo objeto atual e pelo objeto especificado são iguais. |
| static [Guid](./) [Parse](./parse/)(const [String](../string/)\&) | Converte a representação em string especificada de um GUID em um objeto [Guid](./) equivalente. |
| [ArrayPtr](../arrayptr/)\<**uint8_t**\> [ToByteArray](./tobytearray/)() const | Converte o GUID representado pelo objeto atual em um array de bytes. |
| [String](../string/) [ToString](./tostring/)() const | Converte o GUID representado pelo objeto atual para sua representação em string. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Converte o GUID representado pelo objeto atual para sua representação em string usando o formato de string especificado. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const | Converte o GUID representado pelo objeto atual para sua representação em string usando o formato de string e Cultura especificados. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Guid](./)\&) | Tenta converter a string especificada em um objeto [Guid](./). |
|  [~Guid](./~guid/)() | Destrutor. |
## Campos

| Field | Description |
| --- | --- |
| static [Empty](./empty/) | Representa um GUID que tem valor 0. |
## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)