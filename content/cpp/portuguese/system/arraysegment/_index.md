---
title: ArraySegment
second_title: Referência da API Aspose.Slides para C++
description: "Representa um segmento da matriz unidimensional. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 40
url: /pt/system/arraysegment/
---
## ArraySegment classe

Representa um segmento da matriz unidimensional. Esse tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
template<typename T>class ArraySegment : public System::Object
```

### Parâmetros de modelo

| Parâmetro | Descrição |
| --- | --- |
| T | O tipo dos elementos do segmento de array. |

## Métodos

| Método | Descrição |
| --- | --- |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>) |  |
|  [ArraySegment](./arraysegment/)([System::ArrayPtr](../arrayptr/)\<T\>, **int32_t**, **int32_t**) |  |
|  [ArraySegment](./arraysegment/)() |  |
| **bool** [Equals](./equals/)([System::SharedPtr](../sharedptr/)\<[Object](../object/)\>) override |  |
| **bool** [Equals](./equals/)([ArraySegment](./)\<T\>) |  |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C# onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| [System::ArrayPtr](../arrayptr/)\<T\> [get_Array](./get_array/)() const |  |
| **int32_t** [get_Count](./get_count/)() const |  |
| **int32_t** [get_Offset](./get_offset/)() const |  |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Analógico do método C# [Object.GetHashCode()](../object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../object/object/)([Object](../object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| T\& [operator[]](./operator[]/)(**int32_t**) const |  |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Especialização de [Object::ReferenceEquals](../object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| [ArraySegment](./)\<T\> [Slice](./slice/)(**int32_t**, **int32_t**) |  |
| [System::ArrayPtr](../arrayptr/)\<T\> [ToArray](./toarray/)() const |  |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analógico do método C# [Object.ToString()](../object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implementa a construção C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Observações

```cpp
#include <system/array_segment.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<ArraySegment<String>> &segment)
{
  for (auto i = segment->get_Offset(); i < segment->get_Offset() + segment->get_Count(); i++)
  {
    std::cout << segment->get_Array()[i] << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Cria e preenche o array.
  auto array = System::MakeObject<Array<String>>(3);
  array[0] = u"First";
  array[1] = u"Second";
  array[2] = u"Third";

  // Cria o segmento de array que contém o array completo.
  auto fullArray = MakeObject<ArraySegment<String>>(array);

  // Imprime os itens do segmento de array.
  Print(fullArray);

  // Cria o segmento de array.
  auto segment = MakeObject<ArraySegment<String>>(array, 1, 2);

  // Imprime os itens do segmento de array.
  Print(segment);

  return 0;
}
/*
Este exemplo de código produz a seguinte saída:
First Second Third
Second Third
*/
```

## Veja também

* Classe [Object](../object/)
* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)