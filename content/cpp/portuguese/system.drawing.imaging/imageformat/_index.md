---
title: ImageFormat
second_title: Referência da API Aspose.Slides para C++
description: "Representa o formato de arquivo de uma imagem. Objetos desta classe devem ser alocados apenas usando a função System::MakeObject(). Nunca crie instâncias deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre encapsule esta classe em um ponteiro System::SmartPtr e use esse ponteiro ao passá-lo para funções como argumento."
type: docs
weight: 131
url: /pt/system.drawing.imaging/imageformat/
---
## classe ImageFormat

Representa o formato de arquivo de uma imagem. Objetos desta classe devem ser alocados apenas usando a função [System::MakeObject()](../../system/makeobject/). Nunca crie uma instância deste tipo na pilha ou usando o operador new, pois isso resultará em erros de tempo de execução e/ou falhas de asserção. Sempre envolva esta classe em um ponteiro [System::SmartPtr](../../system/smartptr/) e use esse ponteiro para passá-lo a funções como argumento.

```cpp
class ImageFormat : public System::Object
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [Equals](./equals/)([ImageFormatPtr](../imageformatptr/)) const | Determina se os formatos de imagem representados pelos objetos atual e especificado são iguais. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante ao estilo C# onde dois NaNs são considerados iguais, embora de acordo com IEC 60559:1989 NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Apenas para uso interno. |
| static [ImageFormatPtr](../imageformatptr/) [get_Bmp](./get_bmp/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem bitmap. |
| static [ImageFormatPtr](../imageformatptr/) [get_Emf](./get_emf/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de metafile avançado. |
| static [ImageFormatPtr](../imageformatptr/) [get_Exif](./get_exif/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de Arquivo Intercambiável [Image](../../system.drawing/image/) (Exif). |
| static [ImageFormatPtr](../imageformatptr/) [get_Gif](./get_gif/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem [Graphics](../../system.drawing/graphics/) Interchange Format (GIF). |
| [System::Guid](../../system/guid/) [get_Guid](./get_guid/)() const | Retorna o GUID associado ao formato de imagem representado pelo objeto atual. |
| static [ImageFormatPtr](../imageformatptr/) [get_Icon](./get_icon/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem ícone [Windows](../../system.windows/). |
| static [ImageFormatPtr](../imageformatptr/) [get_Jpeg](./get_jpeg/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem Joint Photographic Experts Group (JPEG). |
| static [ImageFormatPtr](../imageformatptr/) [get_MemoryBmp](./get_memorybmp/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de um bitmap na memória. |
| static [ImageFormatPtr](../imageformatptr/) [get_Png](./get_png/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem W3C Portable Network [Graphics](../../system.drawing/graphics/) (PNG). |
| static [ImageFormatPtr](../imageformatptr/) [get_Tiff](./get_tiff/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem Tagged [Image](../../system.drawing/image/) File Format (TIFF). |
| static [ImageFormatPtr](../imageformatptr/) [get_Wmf](./get_wmf/)() | Retorna um ponteiro compartilhado para um objeto [ImageFormat](./) que representa o formato de imagem metafile [Windows](../../system.windows/) (WMF). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico do método C# [Object.GetHashCode()](../../system/object/gethashcode/). Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico da chamada C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ImageFormat](./imageformat/)(const [System::Guid](../../system/guid/)\&) | Constrói uma instância da classe [ImageFormat](./) que representa um formato de imagem associado ao GUID especificado. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico do operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico do método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a cópia ao construir subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado pelo valor especificado. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [System::String](../../system/string/) [ToString](./tostring/)() const | Converte este objeto [ImageFormat](./) em uma string legível por humanos. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destrói o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [Object](../../system/object/)
* Namespace [System::Drawing::Imaging](../)
* Biblioteca [Aspose.Slides](../../)