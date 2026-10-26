---
title: Version
second_title: Referência da API Aspose.Slides para C++
description: "Representa um número de versão. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 1470
url: /pt/system/version/
---
## Classe Version


Representa um número de versão. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
class Version
```

## Métodos

| Método | Descrição |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | Compara as versões representadas pelo objeto atual e pelo objeto especificado. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | Determina se os números de versão representados pelos objetos atual e especificado são iguais. |
| int [get_Build](./get_build/)() const | Retorna o número de compilação. |
| int [get_Major](./get_major/)() const | Retorna a versão principal. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | Retorna o valor de 16 bits alto do número de revisão. |
| int [get_Minor](./get_minor/)() const | Retorna a versão menor. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | Retorna o valor de 16 bits baixo do número de revisão. |
| int [get_Revision](./get_revision/)() const | Retorna o número de revisão. |
| int [GetHashCode](./gethashcode/)() const | Retorna um código hash para o objeto atual. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | Converte a representação em string de um número de versão em uma instância equivalente da classe [Version](./). |
| [String](../string/) [ToString](./tostring/)() const | Retorna a representação em string do número de versão representado pelo objeto atual. |
| [String](../string/) [ToString](./tostring/)(int) const | Retorna a representação em string do número especificado de seções do número de versão representado pelo objeto atual. |
| [Version](./version/)(int, int, int, int) | Constrói uma instância que representa os valores de versão principal, menor, de compilação e de revisão especificados. |
| [Version](./version/)(int, int, int) | Constrói uma instância que representa os valores de versão principal, menor e de compilação especificados. |
| [Version](./version/)(int, int) | Constrói uma instância que representa os valores de versão principal especificados. |
| [Version](./version/)(const [String](../string/)\&) | Constrói uma instância que representa o número de versão representado como uma string. |
| [Version](./version/)() | Constrói uma instância que representa o número de versão 0.0.-1.-1. |
## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)