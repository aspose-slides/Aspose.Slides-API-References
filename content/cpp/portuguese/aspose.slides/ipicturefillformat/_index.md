---
title: IPictureFillFormat
second_title: Aspose.Slides para Referência da API C++
description: Representa um estilo de preenchimento de imagem.
type: docs
weight: 3225
url: /pt/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat classe

Representa um estilo de preenchimento de imagem.

```cpp
class IPictureFillFormat : public Aspose::Slides::IFillParamSource
```

## Métodos

| Método | Descrição |
| --- | --- |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, [Export::PicturesCompression](../../aspose.slides.export/picturescompression/)) | Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| virtual **bool** [CompressImage](./compressimage/)(**bool**, **float**) | Comprime a imagem reduzindo seu tamanho com base no tamanho da forma e na resolução especificada. Opcionalmente, também exclui áreas recortadas. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [DeletePictureCroppedAreas](./deletepicturecroppedareas/)() | Exclui áreas recortadas do preenchimento [Picture](../picture/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compara objetos usando a semântica [Object.Equals](../../system/object/equals/) do C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo referência no estilo C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compara objetos do tipo valor no estilo C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emula a comparação de ponto flutuante no estilo C#, onde dois NaNs são considerados iguais mesmo que, de acordo com IEC 60559:1989, NaN não seja igual a nenhum valor, incluindo NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Somente para uso interno. |
| virtual **float** [get_CropBottom](./get_cropbottom/)() | Retorna o número de porcentagens da altura real da imagem que são recortadas na parte inferior da foto. Leitura **float**. |
| virtual **float** [get_CropLeft](./get_cropleft/)() | Retorna o número de porcentagens da largura real da imagem que são recortadas no lado esquerdo da foto. Leitura **float**. |
| virtual **float** [get_CropRight](./get_cropright/)() | Retorna o número de porcentagens da largura real da imagem que são recortadas no lado direito da foto. Leitura **float**. |
| virtual **float** [get_CropTop](./get_croptop/)() | Retorna o número de porcentagens da altura real da imagem que são recortadas na parte superior da foto. Leitura **float**. |
| virtual **int32_t** [get_Dpi](./get_dpi/)() | Retorna o DPI usado para preencher uma imagem. Leitura **int32_t**. |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesPicture](../islidespicture/)\> [get_Picture](./get_picture/)() | Retorna a imagem. Somente leitura [ISlidesPicture](../islidespicture/). |
| virtual [Aspose::Slides::PictureFillMode](../picturefillmode/) [get_PictureFillMode](./get_picturefillmode/)() | Retorna o modo de preenchimento da imagem. Leitura [Slides::PictureFillMode](../picturefillmode/). |
| virtual **float** [get_StretchOffsetBottom](./get_stretchoffsetbottom/)() | Retorna a borda inferior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Leitura **float**. |
| virtual **float** [get_StretchOffsetLeft](./get_stretchoffsetleft/)() | Retorna a borda esquerda do retângulo de preenchimento definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Leitura **float**. |
| virtual **float** [get_StretchOffsetRight](./get_stretchoffsetright/)() | Retorna a borda direita do retângulo de preenchimento definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Leitura **float**. |
| virtual **float** [get_StretchOffsetTop](./get_stretchoffsettop/)() | Retorna a borda superior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Leitura **float**. |
| virtual [RectangleAlignment](../rectanglealignment/) [get_TileAlignment](./get_tilealignment/)() | Retorna como a textura está alinhada dentro da forma. Esta configuração controla o ponto de início do padrão de textura e como ele se repete pela forma. Leitura [RectangleAlignment](../rectanglealignment/). |
| virtual [Aspose::Slides::TileFlip](../tileflip/) [get_TileFlip](./get_tileflip/)() | Inverte a telha de textura em torno de seu eixo horizontal, vertical ou ambos. Leitura [Slides::TileFlip](../tileflip/). |
| virtual **float** [get_TileOffsetX](./get_tileoffsetx/)() | Retorna o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Leitura **float**. |
| virtual **float** [get_TileOffsetY](./get_tileoffsety/)() | Retorna o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Leitura **float**. |
| virtual **float** [get_TileScaleX](./get_tilescalex/)() | Retorna a escala horizontal para o preenchimento de textura como porcentagem. Leitura **float**. |
| virtual **float** [get_TileScaleY](./get_tilescaley/)() | Retorna a escala vertical para o preenchimento de textura como porcentagem. Leitura **float**. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtém a estrutura de dados do contador de referência associada ao objeto. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analógico ao método [Object.GetHashCode()](../../system/object/gethashcode/) do C#. Permite hash de objetos personalizados. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtém o tipo real do objeto. Analógico à chamada [System.Object.GetType()](../../system/object/gettype/) do C#. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifica se o objeto representa uma instância do tipo descrito por targetType. Analógico ao operador 'is' do C#. |
| void [Lock](../../system/object/lock/)() | Implementa o bloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analógico ao método [Object.MemberwiseClone()](../../system/object/memberwiseclone/) do C#. Permite clonagem de tipos personalizados. |
|  [Object](../../system/object/object/)() | Cria o objeto. Inicializa todas as estruturas de dados internas. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Construtor de cópia. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operador de atribuição. Na verdade não copia nada, apenas inicializa um novo objeto e permite a construção de cópias de subclasses. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compara objetos por referência. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compara por referência um objeto de tipo valor com nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de string e nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Especialização de [Object::ReferenceEquals](../../system/object/referenceequals/) para o caso de strings. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminui o contador de referência compartilhado em um valor especificado. |
| virtual void [set_CropBottom](./set_cropbottom/)(**float**) | Define o número de porcentagens da altura real da imagem que são recortadas na parte inferior da foto. Gravação **float**. |
| virtual void [set_CropLeft](./set_cropleft/)(**float**) | Define o número de porcentagens da largura real da imagem que são recortadas no lado esquerdo da foto. Gravação **float**. |
| virtual void [set_CropRight](./set_cropright/)(**float**) | Define o número de porcentagens da largura real da imagem que são recortadas no lado direito da foto. Gravação **float**. |
| virtual void [set_CropTop](./set_croptop/)(**float**) | Define o número de porcentagens da altura real da imagem que são recortadas na parte superior da foto. Gravação **float**. |
| virtual void [set_Dpi](./set_dpi/)(**int32_t**) | Define o DPI usado para preencher uma imagem. Gravação **int32_t**. |
| virtual void [set_PictureFillMode](./set_picturefillmode/)([Aspose::Slides::PictureFillMode](../picturefillmode/)) | Define o modo de preenchimento da imagem. Gravação [Slides::PictureFillMode](../picturefillmode/). |
| virtual void [set_StretchOffsetBottom](./set_stretchoffsetbottom/)(**float**) | Define a borda inferior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda inferior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Gravação **float**. |
| virtual void [set_StretchOffsetLeft](./set_stretchoffsetleft/)(**float**) | Define a borda esquerda do retângulo de preenchimento definido por um deslocamento percentual a partir da borda esquerda da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Gravação **float**. |
| virtual void [set_StretchOffsetRight](./set_stretchoffsetright/)(**float**) | Define a borda direita do retângulo de preenchimento definido por um deslocamento percentual a partir da borda direita da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Gravação **float**. |
| virtual void [set_StretchOffsetTop](./set_stretchoffsettop/)(**float**) | Define a borda superior do retângulo de preenchimento definido por um deslocamento percentual a partir da borda superior da caixa delimitadora da forma. Uma porcentagem positiva especifica um recuo, enquanto uma porcentagem negativa especifica um sobresalto. Gravação **float**. |
| virtual void [set_TileAlignment](./set_tilealignment/)([RectangleAlignment](../rectanglealignment/)) | Define como a textura está alinhada dentro da forma. Esta configuração controla o ponto de início do padrão de textura e como ele se repete pela forma. Gravação [RectangleAlignment](../rectanglealignment/). |
| virtual void [set_TileFlip](./set_tileflip/)([Aspose::Slides::TileFlip](../tileflip/)) | Inverte a telha de textura em torno de seu eixo horizontal, vertical ou ambos. Gravação [Slides::TileFlip](../tileflip/). |
| virtual void [set_TileOffsetX](./set_tileoffsetx/)(**float**) | Define o deslocamento horizontal da textura a partir da origem da forma em pontos. Um valor positivo move a textura para a direita, enquanto um valor negativo a move para a esquerda. Gravação **float**. |
| virtual void [set_TileOffsetY](./set_tileoffsety/)(**float**) | Define o deslocamento vertical da textura a partir da origem da forma em pontos. Um valor positivo move a textura para baixo, enquanto um valor negativo a move para cima. Gravação **float**. |
| virtual void [set_TileScaleX](./set_tilescalex/)(**float**) | Define a escala horizontal para o preenchimento de textura como porcentagem. Gravação **float**. |
| virtual void [set_TileScaleY](./set_tilescaley/)(**float**) | Define a escala vertical para o preenchimento de textura como porcentagem. Gravação **float**. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Define o n-ésimo argumento de modelo como ponteiro fraco (em vez de compartilhado). Permite alternar ponteiros em contêineres para modo fraco. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtém o valor atual do contador de referência compartilhado. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrementa o contador de referência compartilhado. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decrementa e retorna o contador de referência compartilhado. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analógico ao método [Object.ToString()](../../system/object/tostring/) do C#. Permite converter objetos personalizados em string. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implementa a construção C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implementa o desbloqueio da declaração C# lock(). Chame diretamente ou use o objeto sentinela [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decrementa o contador de referência fraca. Não deve ser chamado diretamente; ao invés disso, use ponteiros inteligentes ou ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Destroi o objeto. Libera todas as estruturas de dados internas. |

## Veja Também

* Classe [IFillParamSource](../ifillparamsource/)
* Namespace [Aspose::Slides](../)
* Biblioteca [Aspose.Slides](../../)