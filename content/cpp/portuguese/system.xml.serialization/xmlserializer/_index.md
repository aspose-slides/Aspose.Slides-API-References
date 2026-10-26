---
title: XmlSerializer
second_title: Referência da API Aspose.Slides para C++
description: "Executa a serialização e desserialização de objetos em e a partir de documentos XML. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 66
url: /pt/system.xml.serialization/xmlserializer/
---
## XmlSerializer classe

Executa a serialização e desserialização de objetos em e a partir de documentos XML. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class XmlSerializer : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [CanDeserialize](./candeserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Verifica se o leitor específico está em estado desserializável. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>) | Desserializa documento XML em objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextReader](../../system.io/textreader/)\>) | Desserializa documento XML em objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>) | Desserializa documento XML em objeto. |
| [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Deserialize](./deserialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlReader](../../system.xml/xmlreader/)\>, [String](../../system/string/)) | Desserializa documento XML em objeto. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, segundo IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[IO::TextWriter](../../system.io/textwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/)) | Serializa o documento em XML. |
| void [Serialize](./serialize/)([System::SharedPtr](../../system/sharedptr/)\<[XmlWriter](../../system.xml/xmlwriter/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [System::SharedPtr](../../system/sharedptr/)\<[XmlSerializerNamespaces](../xmlserializernamespaces/)\>, [String](../../system/string/), [String](../../system/string/)) | Serializa o documento em XML. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés, use smart pointers ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés, use smart pointers ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés, use smart pointers ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés, use smart pointers ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Campos

| Campo | Descrição |
| --- | --- |
| static [EncodingNamespace](./encodingnamespace/) | Nome do namespace de codificação. |
| static [WsdlNamespace](./wsdlnamespace/) | Nome do namespace WSDL. |
| static [WsdlTypesNamespace](./wsdltypesnamespace/) | Nome do namespace de tipos WSDL. |

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Xml::Serialization](../)
* Biblioteca [Aspose.Slides](../../)