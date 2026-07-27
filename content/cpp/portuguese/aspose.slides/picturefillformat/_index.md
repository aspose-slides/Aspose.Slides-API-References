---
title: PictureFillFormat
second_title: Referência da API Aspose.Slides para C++
description: Representa um estilo de preenchimento por imagem.
type: docs
weight: 4720
url: /pt/aspose.slides/picturefillformat/
---
## PictureFillFormat classe


Representa um estilo de preenchimento por imagem.

```cpp
class PictureFillFormat : public Aspose::Slides::PVIObject,
                          public Aspose::Slides::IPictureFillFormat
```

## Métodos

| Método | Descrição |
| --- | --- |
| **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) override | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| **bool** [CompressImage](./compressimage/)(**bool**, **float**) override | Compacta a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() override | Exclui áreas recortadas do preenchimento [Picture](../picture/). |
| **bool** [Equals](../pviobject/equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | Compara com o objeto especificado. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos de tipo referência no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais embora, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| **float** [get_CropBottom](./get_cropbottom/)() override | Retorna o número de porcento da altura real da imagem que são recortados na parte inferior da foto. Leitura **float**. |
| **float** [get_CropLeft](./get_cropleft/)() override | Retorna o número de porcento da largura real da imagem que são recortados no lado esquerdo da foto. Leitura **float**. |
| **float** [get_CropRight](./get_cropright/)() override | Retorna o número de porcento da largura real da imagem que são recortados no lado direito da foto. Leitura **float**. |
| **float** [get_CropTop](./get_croptop/)() override | Retorna o número de porcento da altura real da imagem que são recortados na parte superior da foto. Leitura **float**. |
| **int32_t** [get_Dpi](./get_dpi/)() override | Retorna o dpi usado para preencher uma foto. Leitura **int32_t**. |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Retorna o objeto Parent_Immediate. Somente leitura [IDOMObject](../idomobject/). |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | Retorna o pai [IPresentationComponent](../ipresentationcomponent/). Somente leitura [IPresentationComponent](../ipresentationcomponent/). |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() override | Retorna a imagem. Somente leitura [ISlidesPicture](../islidespicture/). |
| [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() override | Retorna o modo de preenchimento da imagem. Leitura [Slides::PictureFillMode](../picturefillmode/). |
| **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() override | Retorna a borda inferior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Leitura **float**. |
| **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() override | Retorna a borda esquerda do retângulo de preenchimento definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Leitura **float**. |
| **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() override | Retorna a borda direita do retângulo de preenchimento definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Leitura **float**. |
| **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() override | Retorna a borda superior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Leitura **float**. |
| [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() override | Retorna como a textura está alinhada dentro da forma. Esta configuração controla o ponto inicial do padrão de textura e como ele se repete ao longo da forma. Leitura [RectangleAlignment](../rectanglealignment/). |
| [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() override | Inverte o bloco de textura ao redor de seu eixo horizontal, vertical ou ambos. Leitura [Slides::TileFlip](../tileflip/). |
| **float** [get_TileOffsetX](./get_tileoffsetx/)() override | Retorna o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo move-a para a esquerda. Leitura **float**. |
| **float** [get_TileOffsetY](./get_tileoffsety/)() override | Retorna o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo move-a para cima. Leitura **float**. |
| **float** [get_TileScaleX](./get_tilescalex/)() override | Retorna a escala horizontal para o preenchimento da textura como porcentagem. Leitura **float**. |
| **float** [get_TileScaleY](./get_tilescaley/)() override | Retorna a escala vertical para o preenchimento da textura como porcentagem. Leitura **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| **int32_t** [GetHashCode](../pviobject/gethashcode/)() const override | Retorna o código de hash. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Análogo à chamada C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Análogo ao operador C# 'is'. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Análogo ao método C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permite clonar tipos personalizados. |
| [Object](../../system/object/object/)() | Cria objeto. Inicializa todas as estruturas de dados internas. |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade, não copia nada, apenas inicializa um novo objeto e permite a cópia na construção de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade, não copia nada, apenas inicializa um novo objeto e permite a cópia na construção de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhada pelo valor especificado. |
| void [set_CropBottom](./set_cropbottom/)(**float**) override | Define o número de porcento da altura real da imagem que são recortados na parte inferior da foto. Grava **float**. |
| void [set_CropLeft](./set_cropleft/)(**float**) override | Define o número de porcento da largura real da imagem que são recortados no lado esquerdo da foto. Grava **float**. |
| void [set_CropRight](./set_cropright/)(**float**) override | Define o número de porcento da largura real da imagem que são recortados no lado direito da foto. Grava **float**. |
| void [set_CropTop](./set_croptop/)(**float**) override | Define o número de porcento da altura real da imagem que são recortados na parte superior da foto. Grava **float**. |
| void [set_Dpi](./set_dpi/)(**int32_t**) override | Define o dpi usado para preencher uma foto. Grava **int32_t**. |
| void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) override | Define o modo de preenchimento da imagem. Grava [Slides::PictureFillMode](../picturefillmode/). |
| void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) override | Define a borda inferior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Grava **float**. |
| void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) override | Define a borda esquerda do retângulo de preenchimento definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Grava **float**. |
| void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) override | Define a borda direita do retângulo de preenchimento definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Grava **float**. |
| void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) override | Define a borda superior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um deslocamento externo. Grava **float**. |
| void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) override | Define como a textura está alinhada dentro da forma. Esta configuração controla o ponto inicial do padrão de textura e como ele se repete ao longo da forma. Grava [RectangleAlignment](../rectanglealignment/). |
| void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) override | Inverte o bloco de textura ao redor de seu eixo horizontal, vertical ou ambos. Grava [Slides::TileFlip](../tileflip/). |
| void [set_TileOffsetX](./set_tileoffsetx/)(**float**) override | Define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo move-a para a esquerda. Grava **float**. |
| void [set_TileOffsetY](./set_tileoffsety/)(**float**) override | Define o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo move-a para cima. Grava **float**. |
| void [set_TileScaleX](./set_tilescalex/)(**float**) override | Define a escala horizontal para o preenchimento da textura como porcentagem. Grava **float**. |
| void [set_TileScaleY](./set_tilescaley/)(**float**) override | Define a escala vertical para o preenchimento da textura como porcentagem. Grava **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de template como um ponteiro fraco (em vez de compartilhado). Permite trocar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhada. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhada. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Análogo ao método C# [Object.ToString()](../../system/object/tostring/). Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da instrução C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [PVIObject](../pviobject/)
* Classe [IPictureFillFormat](../ipicturefillformat/)
* Namespace [Aspose::Slides](../)
* Library [Aspose.Slides](../../)