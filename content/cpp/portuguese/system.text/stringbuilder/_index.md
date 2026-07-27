---
title: StringBuilder
second_title: Referência da API Aspose.Slides para C++
description: "Buffer para acumular partes de string. Esse tipo pode ser alocado tanto na pilha como tipo de valor quanto no heap usando a função System::MakeObject(). Depois que o objeto é alocado, nunca misture esses dois casos de uso: ter ponteiros SmartPtr para objetos alocados na pilha é estritamente proibido."
type: docs
weight: 326
url: /pt/system.text/stringbuilder/
---
## StringBuilder classe


[Buffer](../../system/buffer/) para acumular partes de string. Esse tipo pode ser alocado tanto na pilha como tipo de valor quanto no heap usando a função [System::MakeObject()](../../system/makeobject/). Depois que o objeto é alocado, nunca misture esses dois casos de uso: ter ponteiros [SmartPtr](../../system/smartptr/) para objetos alocados na pilha é estritamente proibido.

```cpp
class StringBuilder : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| [StringBuilder](./) * [Append](./append/)(char_t) | Adiciona um caractere ao construtor. |
| [StringBuilder](./) * [Append](./append/)(char_t, int) | Adiciona caracteres ao construtor. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Adiciona um array de caracteres ao construtor. |
| [StringBuilder](./) * [Append](./append/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Adiciona um trecho de array de caracteres ao construtor. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&) | Adiciona uma string ao construtor. |
| [StringBuilder](./) * [Append](./append/)(const [String](../../system/string/)\&, int, int) | Adiciona um trecho de string ao construtor. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<T\>\&) | Adiciona a representação em string do objeto ao construtor. |
| [StringBuilder](./) * [Append](./append/)(const [SharedPtr](../../system/sharedptr/)\<[StringBuilder](./)\>\&) | Adiciona o conteúdo do construtor ao construtor. |
| [StringBuilder](./) * [Append](./append/)(**float**) | Adiciona um valor de ponto flutuante ao construtor. |
| [StringBuilder](./) * [Append](./append/)(**double**) | Adiciona um valor de ponto flutuante ao construtor. |
| [StringBuilder](./) * [Append](./append/)(int) | Adiciona um valor inteiro ao construtor. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Append](./append/)(T) | Adiciona um valor aritmético ao construtor. |
| std::enable_if\<std::is_enum\<E\>::value, [StringBuilder](./) *\>::type [Append](./append/)(E) | Adiciona a representação em string do valor enum ao construtor. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [String](../../system/string/)\&, const TArgs\&...) | Anexa uma string formatada ao construtor. |
| [StringBuilder](./) * [AppendFormat](./appendformat/)(const [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\>\&, const [String](../../system/string/)\&, const TArgs\&...) | Anexa uma string formatada ao construtor. |
| [StringBuilder](./) * [AppendLine](./appendline/)() | Anexa o caractere de nova linha ao construtor. |
| [StringBuilder](./) * [AppendLine](./appendline/)(const [String](../../system/string/)\&) | Anexa uma string seguida do caractere de nova linha ao construtor. |
| [StringBuilder](./) * [Clear](./clear/)() | Remove todos os caracteres do construtor. |
| void [CopyTo](./copyto/)(int, [System::ArrayPtr](../../system/arrayptr/)\<char_t\> const\&, int, int) | Copia os dados do construtor para posições existentes do array. |
| **int32_t** [EnsureCapacity](./ensurecapacity/)(**int32_t**) | Garante que a capacidade desta instância de [System.Text.StringBuilder](./) seja pelo menos o valor especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C#, onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| int [get_Capacity](./get_capacity/)() const | Obtém a capacidade atual do construtor de strings. |
| int [get_Length](./get_length/)() const | Obtém o comprimento da string atualmente no construtor. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Análogo ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| char_t [idx_get](./idx_get/)(int) const | Obtém o caractere na posição especificada. |
| void [idx_set](./idx_set/)(int, char_t) | Define o caractere na posição especificada. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [String](../../system/string/)\&) | Insere uma string na posição fixa do construtor. |
| [StringBuilder](./) * [Insert](./insert/)(**int32_t**, const [String](../../system/string/)\&, **int32_t**) | Insere uma string repetida na posição fixa do construtor. |
| [StringBuilder](./) * [Insert](./insert/)(int, char_t) | Insere um caractere na posição fixa do construtor. |
| [StringBuilder](./) * [Insert](./insert/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<char_t\>\&, int, int) | Insere caracteres na posição fixa do construtor. |
| std::enable_if\<std::is_arithmetic\<T\>::value, [StringBuilder](./) *\>::type [Insert](./insert/)(int, T) | Insere um valor na posição fixa do construtor. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| char_t [operator[]](./operator[]/)(int) const | Obtém o caractere na posição especificada. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| [StringBuilder](./) * [Remove](./remove/)(int, int) | Remove fragmento do construtor. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Substitui substring através do construtor. |
| [StringBuilder](./) * [Replace](./replace/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, int, int) | Substitui substring através do intervalo do construtor. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t) | Substitui caractere através do construtor. |
| [StringBuilder](./) * [Replace](./replace/)(char_t, char_t, int, int) | Substitui caractere através do intervalo do construtor. |
| void [set_Capacity](./set_capacity/)(int) | Define a capacidade atual do construtor de strings. |
| void [set_Length](./set_length/)(int) | Trunca ou estende o construtor de strings ao comprimento especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
|  [StringBuilder](./stringbuilder/)() | Construtor. |
|  [StringBuilder](./stringbuilder/)(int) | Construtor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&) | Construtor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int) | Construtor. |
|  [StringBuilder](./stringbuilder/)(const [String](../../system/string/)\&, int, int, int) | Construtor. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Obtém a string atualmente contida no construtor. |
| [String](../../system/string/) [ToString](./tostring/)(int, int) const | Obtém o substring atualmente contido no construtor. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |
|  [~StringBuilder](./~stringbuilder/)() | Destrutor. |
## Ver também

* Classe [Object](../../system/object/)
* Namespace [System::Text](../)
* Biblioteca [Aspose.Slides](../../)