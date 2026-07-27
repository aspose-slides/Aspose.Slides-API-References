---
title: XmlWriterSettings
second_title: Referência da API Aspose.Slides para C++
description: "Especifica um conjunto de recursos a suportar no objeto XmlWriter criado pelo método XmlWriter::Create."
type: docs
weight: 586
url: /pt/system.xml/xmlwritersettings/
---
## XmlWriterSettings classe

Especifica um conjunto de recursos a suportar no objeto [XmlWriter](../xmlwriter/) criado pelo método [XmlWriter::Create](../xmlwriter/create/).

```cpp
class XmlWriterSettings : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[XmlWriterSettings](./)\> [Clone](./clone/)() | Cria uma cópia da instância [XmlWriterSettings](./). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais ainda que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais ainda que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **bool** [get_CheckCharacters](./get_checkcharacters/)() | Retorna um valor que indica se o escritor XML deve verificar se todos os caracteres no documento estão em conformidade com a seção "2.2 Characters" da [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) da W3C. |
| **bool** [get_CloseOutput](./get_closeoutput/)() | Retorna um valor indicando se o [XmlWriter](../xmlwriter/) também deve fechar o fluxo subjacente ou o TextWriter quando o método [XmlWriter::Close](../xmlwriter/close/) for chamado. |
| [System::Xml::ConformanceLevel](../conformancelevel/) [get_ConformanceLevel](./get_conformancelevel/)() | Retorna o nível de conformidade que o escritor XML verifica na saída XML. |
| **bool** [get_DoNotEscapeUriAttributes](./get_donotescapeuriattributes/)() | Retorna um valor que indica se o [XmlWriter](../xmlwriter/) não escapará atributos de URI. |
| [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Retorna o tipo de codificação de texto a ser usado. |
| **bool** [get_Indent](./get_indent/)() | Retorna um valor indicando se os elementos devem ser recuados. |
| [String](../../system/string/) [get_IndentChars](./get_indentchars/)() | Retorna a cadeia de caracteres a ser usada ao recuar. Esta configuração é usada quando o valor [XmlWriterSettings::set_Indent](./set_indent/) está definido como **true**. |
| [System::Xml::NamespaceHandling](../namespacehandling/) [get_NamespaceHandling](./get_namespacehandling/)() | Retorna um valor que indica se o [XmlWriter](../xmlwriter/) deve remover declarações de namespace duplicadas ao escrever conteúdo XML. O comportamento padrão é que o escritor emita todas as declarações de namespace presentes no resolvedor de namespaces do escritor. |
| [String](../../system/string/) [get_NewLineChars](./get_newlinechars/)() | Retorna a cadeia de caracteres a ser usada para quebras de linha. |
| [System::Xml::NewLineHandling](../newlinehandling/) [get_NewLineHandling](./get_newlinehandling/)() | Retorna um valor indicando se as quebras de linha devem ser normalizadas na saída. |
| **bool** [get_NewLineOnAttributes](./get_newlineonattributes/)() | Retorna um valor indicando se os atributos devem ser escritos em uma nova linha. |
| **bool** [get_OmitXmlDeclaration](./get_omitxmldeclaration/)() | Retorna um valor indicando se deve omitir a declaração XML. |
| [XmlOutputMethod](../xmloutputmethod/) [get_OutputMethod](./get_outputmethod/)() | Retorna o método usado para serializar a saída [XmlWriter](../xmlwriter/). |
| **bool** [get_WriteEndDocumentOnClose](./get_writeenddocumentonclose/)() | Retorna um valor que indica se o [XmlWriter](../xmlwriter/) adicionará tags de fechamento a todas as tags de elemento não fechadas quando o método [XmlWriter::Close](../xmlwriter/close/) for chamado. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogia ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Habilita hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analogia à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analogia ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogia ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construtores de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite copiar construtores de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [Reset](./reset/)() | Redefine os membros da classe de configurações para seus valores padrão. |
| void [set_CheckCharacters](./set_checkcharacters/)(**bool**) | Define um valor que indica se o escritor XML deve verificar se todos os caracteres no documento estão em conformidade com a seção "2.2 Characters" da [XML 1.0 Recommendation](https://www.w3.org/TR/REC-xml/#charsets) da W3C. |
| void [set_CloseOutput](./set_closeoutput/)(**bool**) | Define um valor indicando se o [XmlWriter](../xmlwriter/) também deve fechar o fluxo subjacente ou o TextWriter quando o método [XmlWriter::Close](../xmlwriter/close/) for chamado. |
| void [set_ConformanceLevel](./set_conformancelevel/)([System::Xml::ConformanceLevel](../conformancelevel/)) | Define o nível de conformidade que o escritor XML verifica na saída XML. |
| void [set_DoNotEscapeUriAttributes](./set_donotescapeuriattributes/)(**bool**) | Define um valor que indica se o [XmlWriter](../xmlwriter/) não escapará atributos de URI. |
| void [set_Encoding](./set_encoding/)(const [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\>\&) | Define o tipo de codificação de texto a ser usado. |
| void [set_Indent](./set_indent/)(**bool**) | Define um valor indicando se os elementos devem ser recuados. |
| void [set_IndentChars](./set_indentchars/)(const [String](../../system/string/)\&) | Define a cadeia de caracteres a ser usada ao recuar. Esta configuração é usada quando o valor [XmlWriterSettings::set_Indent](./set_indent/) está definido como **true**. |
| void [set_NamespaceHandling](./set_namespacehandling/)([System::Xml::NamespaceHandling](../namespacehandling/)) | Define um valor que indica se o [XmlWriter](../xmlwriter/) deve remover declarações de namespace duplicadas ao escrever conteúdo XML. O comportamento padrão é que o escritor emita todas as declarações de namespace presentes no resolvedor de namespaces do escritor. |
| void [set_NewLineChars](./set_newlinechars/)(const [String](../../system/string/)\&) | Define a cadeia de caracteres a ser usada para quebras de linha. |
| void [set_NewLineHandling](./set_newlinehandling/)([System::Xml::NewLineHandling](../newlinehandling/)) | Define um valor indicando se as quebras de linha devem ser normalizadas na saída. |
| void [set_NewLineOnAttributes](./set_newlineonattributes/)(**bool**) | Define um valor indicando se os atributos devem ser escritos em uma nova linha. |
| void [set_OmitXmlDeclaration](./set_omitxmldeclaration/)(**bool**) | Define um valor indicando se deve omitir a declaração XML. |
| void [set_WriteEndDocumentOnClose](./set_writeenddocumentonclose/)(**bool**) | Define um valor que indica se o [XmlWriter](../xmlwriter/) adicionará tags de fechamento a todas as tags de elemento não fechadas quando o método [XmlWriter::Close](../xmlwriter/close/) for chamado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como um ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogia ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução lock() do C#. Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; em vez disso, use ponteiros inteligentes ou ThisProtector. |
| [XmlWriterSettings](./xmlwritersettings/)() | Inicializa uma nova instância da classe [XmlWriterSettings](./). |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Tipos definidos

| Typedef | Descrição |
| --- | --- |
| [Ptr](./ptr/) | Um alias para ponteiro compartilhado a uma instância desta classe. |

## Observações

Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento. 

## Veja Também

* Classe [Object](../../system/object/)
* Espaço de nomes [System::Xml](../)
* Library [Aspose.Slides](../../)