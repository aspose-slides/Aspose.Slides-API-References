---
title: ColorMatrix
second_title: Referência da API Aspose.Slides para C++
description: "Representa uma matriz 5x5 que contém as coordenadas para o espaço de cores RGBAW. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro para passá-lo a funções como argumento."
type: docs
weight: 27
url: /pt/system.drawing.imaging/colormatrix/
---
## ColorMatrix classe

Representa uma matriz 5x5 que contém as coordenadas para o espaço de cores RGBAW. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando operator new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ColorMatrix : public System::Object
```

## Métodos

| Method | Description |
| --- | --- |
|  [ColorMatrix](./colormatrix/)() | Constrói uma nova instância da classe [ColorMatrix](./) e a inicializa com os valores da matriz identidade. |
|  [ColorMatrix](./colormatrix/)(const [System::ArrayPtr](../../system/arrayptr/)\<[System::ArrayPtr](../../system/arrayptr/)\<**float**\>\>\&) | Constrói uma nova instância da classe [ColorMatrix](./) e a inicializa com os valores especificados. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora segundo IEC 60559:1989 NaN não seja igual a nenhum valor, inclusive NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| **float** [get_Matrix00](./get_matrix00/)() const | Retorna um valor na linha 0-th e coluna 0-th. |
| **float** [get_Matrix01](./get_matrix01/)() const | Retorna um valor na linha 0-th e coluna 1-st. |
| **float** [get_Matrix02](./get_matrix02/)() const | Retorna um valor na linha 0-th e coluna 2-nd. |
| **float** [get_Matrix03](./get_matrix03/)() const | Retorna um valor na linha 0-th e coluna 3-rd. |
| **float** [get_Matrix04](./get_matrix04/)() const | Retorna um valor na linha 0-th e coluna 4-th. |
| **float** [get_Matrix10](./get_matrix10/)() const | Retorna um valor na linha 1-st e coluna 0-th. |
| **float** [get_Matrix11](./get_matrix11/)() const | Retorna um valor na linha 1-st e coluna 1-st. |
| **float** [get_Matrix12](./get_matrix12/)() const | Retorna um valor na linha 1-st e coluna 2-nd. |
| **float** [get_Matrix13](./get_matrix13/)() const | Retorna um valor na linha 1-st e coluna 3-rd. |
| **float** [get_Matrix14](./get_matrix14/)() const | Retorna um valor na linha 1-st e coluna 4-th. |
| **float** [get_Matrix20](./get_matrix20/)() const | Retorna um valor na linha 2-nd e coluna 0-th. |
| **float** [get_Matrix21](./get_matrix21/)() const | Retorna um valor na linha 2-nd e coluna 1-st. |
| **float** [get_Matrix22](./get_matrix22/)() const | Retorna um valor na linha 2-nd e coluna 2-nd. |
| **float** [get_Matrix23](./get_matrix23/)() const | Retorna um valor na linha 2-nd e coluna 3-rd. |
| **float** [get_Matrix24](./get_matrix24/)() const | Retorna um valor na linha 2-nd e coluna 4-th. |
| **float** [get_Matrix30](./get_matrix30/)() const | Retorna um valor na linha 3-rd e coluna 0-th. |
| **float** [get_Matrix31](./get_matrix31/)() const | Retorna um valor na linha 3-rd e coluna 1-st. |
| **float** [get_Matrix32](./get_matrix32/)() const | Retorna um valor na linha 3-rd e coluna 2-nd. |
| **float** [get_Matrix33](./get_matrix33/)() const | Retorna um valor na linha 3-rd e coluna 3-rd. |
| **float** [get_Matrix34](./get_matrix34/)() const | Retorna um valor na linha 3-rd e coluna 4-th. |
| **float** [get_Matrix40](./get_matrix40/)() const | Retorna um valor na linha 4-th e coluna 0-th. |
| **float** [get_Matrix41](./get_matrix41/)() const | Retorna um valor na linha 4-th e coluna 1-st. |
| **float** [get_Matrix42](./get_matrix42/)() const | Retorna um valor na linha 4-th e coluna 2-nd. |
| **float** [get_Matrix43](./get_matrix43/)() const | Retorna um valor na linha 4-th e coluna 3-rd. |
| **float** [get_Matrix44](./get_matrix44/)() const | Retorna um valor na linha 4-th e coluna 4-th. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógica ao método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógica à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| **float** [idx_get](./idx_get/)(int, int) | Retorna um valor na linha e coluna especificadas. |
| **float** [idx_set](./idx_set/)(int, int, **float**) | Define o valor especificado na localização indicada da matriz. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógica ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógica ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Não copia nada, apenas inicializa um novo objeto e permite a cópia de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_Matrix00](./set_matrix00/)(**float**) | Define um valor na linha 0-th e coluna 0-th. |
| void [set_Matrix01](./set_matrix01/)(**float**) | Define um valor na linha 0-th e coluna 1-st. |
| void [set_Matrix02](./set_matrix02/)(**float**) | Define um valor na linha 0-th e coluna 2-nd. |
| void [set_Matrix03](./set_matrix03/)(**float**) | Define um valor na linha 0-th e coluna 3-rd. |
| void [set_Matrix04](./set_matrix04/)(**float**) | Define um valor na linha 0-th e coluna 4-th. |
| void [set_Matrix10](./set_matrix10/)(**float**) | Define um valor na linha 1-st e coluna 0-th. |
| void [set_Matrix11](./set_matrix11/)(**float**) | Define um valor na linha 1-st e coluna 1-st. |
| void [set_Matrix12](./set_matrix12/)(**float**) | Define um valor na linha 1-st e coluna 2-nd. |
| void [set_Matrix13](./set_matrix13/)(**float**) | Define um valor na linha 1-st e coluna 3-rd. |
| void [set_Matrix14](./set_matrix14/)(**float**) | Define um valor na linha 1-st e coluna 4-th. |
| void [set_Matrix20](./set_matrix20/)(**float**) | Define um valor na linha 2-nd e coluna 0-th. |
| void [set_Matrix21](./set_matrix21/)(**float**) | Define um valor na linha 2-nd e coluna 1-st. |
| void [set_Matrix22](./set_matrix22/)(**float**) | Define um valor na linha 2-nd e coluna 2-nd. |
| void [set_Matrix23](./set_matrix23/)(**float**) | Define um valor na linha 2-nd e coluna 3-rd. |
| void [set_Matrix24](./set_matrix24/)(**float**) | Define um valor na linha 2-nd e coluna 4-th. |
| void [set_Matrix30](./set_matrix30/)(**float**) | Define um valor na linha 3-rd e coluna 0-th. |
| void [set_Matrix31](./set_matrix31/)(**float**) | Define um valor na linha 3-rd e coluna 1-st. |
| void [set_Matrix32](./set_matrix32/)(**float**) | Define um valor na linha 3-rd e coluna 2-nd. |
| void [set_Matrix33](./set_matrix33/)(**float**) | Define um valor na linha 3-rd e coluna 3-rd. |
| void [set_Matrix34](./set_matrix34/)(**float**) | Define um valor na linha 3-rd e coluna 4-th. |
| void [set_Matrix40](./set_matrix40/)(**float**) | Define um valor na linha 4-th e coluna 0-th. |
| void [set_Matrix41](./set_matrix41/)(**float**) | Define um valor na linha 4-th e coluna 1-st. |
| void [set_Matrix42](./set_matrix42/)(**float**) | Define um valor na linha 4-th e coluna 2-nd. |
| void [set_Matrix43](./set_matrix43/)(**float**) | Define um valor na linha 4-th e coluna 3-rd. |
| void [set_Matrix44](./set_matrix44/)(**float**) | Define um valor na linha 4-th e coluna 4-th. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite mudar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógica ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados para string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)