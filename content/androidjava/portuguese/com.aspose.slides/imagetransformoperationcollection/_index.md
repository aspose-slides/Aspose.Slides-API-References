---
title: ImageTransformOperationCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de efeitos aplicados a uma imagem.
type: docs
url: /pt/com.aspose.slides/imagetransformoperationcollection/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperationCollection](../../com.aspose.slides/iimagetransformoperationcollection)
```
public final class ImageTransformOperationCollection extends PVIObject implements IImageTransformOperationCollection
```

Representa uma coleção de efeitos aplicados a uma imagem.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [get_Item(int index)](#get-Item-int-) | Retorna um [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) da coleção pelo seu índice. |
| [removeAt(int index)](#removeAt-int-) | Remove um efeito de imagem de uma coleção no índice especificado. |
| [addAlphaBiLevelEffect(float threshold)](#addAlphaBiLevelEffect-float-) | Adiciona o novo efeito Alpha Bi-Level ao final de uma coleção. |
| [addAlphaCeilingEffect()](#addAlphaCeilingEffect--) | Adiciona o novo efeito Alpha Ceiling ao final de uma coleção. |
| [addAlphaFloorEffect()](#addAlphaFloorEffect--) | Adiciona o novo efeito Alpha Floor ao final de uma coleção. |
| [addAlphaInverseEffect()](#addAlphaInverseEffect--) | Adiciona o novo efeito Alpha Inverse ao final de uma coleção. |
| [addAlphaModulateEffect()](#addAlphaModulateEffect--) | Adiciona o novo efeito Alpha Modulate ao final de uma coleção. |
| [addAlphaModulateFixedEffect(float amount)](#addAlphaModulateFixedEffect-float-) | Adiciona o novo efeito Alpha Modulate Fixed ao final de uma coleção. |
| [addAlphaReplaceEffect(float alpha)](#addAlphaReplaceEffect-float-) | Adiciona o novo efeito Alpha Replace ao final de uma coleção. |
| [addBiLevelEffect(float threshold)](#addBiLevelEffect-float-) | Adiciona o novo efeito Bi-Level (preto/branco) ao final de uma coleção. |
| [addBlurEffect(double radius, boolean grow)](#addBlurEffect-double-boolean-) | Adiciona o novo efeito Blur ao final de uma coleção. |
| [addColorChangeEffect()](#addColorChangeEffect--) | Adiciona o novo efeito Color Change ao final de uma coleção. |
| [addColorReplaceEffect()](#addColorReplaceEffect--) | Adiciona o novo efeito Color Replacement ao final de uma coleção. |
| [addDuotoneEffect()](#addDuotoneEffect--) | Adiciona o novo efeito Duotone ao final de uma coleção. |
| [addFillOverlayEffect()](#addFillOverlayEffect--) | Adiciona o novo efeito Fill Overlay ao final de uma coleção. |
| [addGrayScaleEffect()](#addGrayScaleEffect--) | Adiciona o novo efeito Gray Scale ao final de uma coleção. |
| [addHSLEffect(float hue, float saturation, float luminance)](#addHSLEffect-float-float-float-) | Adiciona o novo efeito Hue/Saturation/Luminance ao final de uma coleção. |
| [addLuminanceEffect(float brightness, float contrast)](#addLuminanceEffect-float-float-) | Adiciona o novo efeito Luminance ao final de uma coleção. |
| [addTintEffect(float hue, float amount)](#addTintEffect-float-float-) | Adiciona o novo efeito Tint ao final de uma coleção. |
| [addBrightnessContrastEffect(float brightness, float contrast)](#addBrightnessContrastEffect-float-float-) | Adiciona o novo efeito BrightnessContrast ao final de uma coleção. |
| [size()](#size--) | Retorna o número de efeitos de imagem em uma coleção. |
| [isReadOnly()](#isReadOnly--) | Obtém um valor indicando se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. |
| [addItem(IImageTransformOperation operation)](#addItem-com.aspose.slides.IImageTransformOperation-) | Adiciona o novo efeito de imagem ao final de uma coleção. |
| [clear()](#clear--) | Remove todos os efeitos de imagem de uma coleção. |
| [containsItem(IImageTransformOperation item)](#containsItem-com.aspose.slides.IImageTransformOperation-) | Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico. |
| [copyToTArray(IImageTransformOperation[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IImageTransformOperation---int-) | Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico. |
| [removeItem(IImageTransformOperation item)](#removeItem-com.aspose.slides.IImageTransformOperation-) | Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para a coleção inteira. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Retorna:**
long
### get_Item(int index) {#get-Item-int-}
```
public final IImageTransformOperation get_Item(int index)
```


Retorna um [ImageTransformOperation](../../com.aspose.slides/imagetransformoperation) da coleção pelo seu índice.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice do elemento. |

**Retorna:**
[IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) - O objeto [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove um efeito de imagem de uma coleção no índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice de um efeito de imagem que deve ser excluído. |

### addAlphaBiLevelEffect(float threshold) {#addAlphaBiLevelEffect-float-}
```
public final IAlphaBiLevel addAlphaBiLevelEffect(float threshold)
```


Adiciona o novo efeito Alpha Bi-Level ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | O valor de limiar para o efeito alpha bi-level. |

**Retorna:**
[IAlphaBiLevel](../../com.aspose.slides/ialphabilevel) - Índice do novo efeito de imagem na coleção.
### addAlphaCeilingEffect() {#addAlphaCeilingEffect--}
```
public final IAlphaCeiling addAlphaCeilingEffect()
```


Adiciona o novo efeito Alpha Ceiling ao final de uma coleção.

**Retorna:**
[IAlphaCeiling](../../com.aspose.slides/ialphaceiling) - Índice do novo efeito de imagem na coleção.
### addAlphaFloorEffect() {#addAlphaFloorEffect--}
```
public final IAlphaFloor addAlphaFloorEffect()
```


Adiciona o novo efeito Alpha Floor ao final de uma coleção.

**Retorna:**
[IAlphaFloor](../../com.aspose.slides/ialphafloor) - Índice do novo efeito de imagem na coleção.
### addAlphaInverseEffect() {#addAlphaInverseEffect--}
```
public final IAlphaInverse addAlphaInverseEffect()
```


Adiciona o novo efeito Alpha Inverse ao final de uma coleção.

**Retorna:**
[IAlphaInverse](../../com.aspose.slides/ialphainverse) - Índice do novo efeito de imagem na coleção.
### addAlphaModulateEffect() {#addAlphaModulateEffect--}
```
public final IAlphaModulate addAlphaModulateEffect()
```


Adiciona o novo efeito Alpha Modulate ao final de uma coleção.

**Retorna:**
[IAlphaModulate](../../com.aspose.slides/ialphamodulate) - Índice do novo efeito de imagem na coleção.
### addAlphaModulateFixedEffect(float amount) {#addAlphaModulateFixedEffect-float-}
```
public final IAlphaModulateFixed addAlphaModulateFixedEffect(float amount)
```


Adiciona o novo efeito Alpha Modulate Fixed ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| amount | float | A quantidade percentual para escalar o alpha. |

**Retorna:**
[IAlphaModulateFixed](../../com.aspose.slides/ialphamodulatefixed) - Índice do novo efeito de imagem na coleção.
### addAlphaReplaceEffect(float alpha) {#addAlphaReplaceEffect-float-}
```
public final IAlphaReplace addAlphaReplaceEffect(float alpha)
```


Adiciona o novo efeito Alpha Replace ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| alpha | float | O novo valor de opacidade. |

**Retorna:**
[IAlphaReplace](../../com.aspose.slides/ialphareplace) - Índice do novo efeito de imagem na coleção.
### addBiLevelEffect(float threshold) {#addBiLevelEffect-float-}
```
public final IBiLevel addBiLevelEffect(float threshold)
```


Adiciona o novo efeito Bi-Level (preto/branco) ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| threshold | float | O limiar de luminância para o efeito Bi-Level. Valores maiores ou iguais ao limiar são definidos como branco. Valores menores que o limiar são definidos como preto. |

**Retorna:**
[IBiLevel](../../com.aspose.slides/ibilevel) - Índice do novo efeito de imagem na coleção.
### addBlurEffect(double radius, boolean grow) {#addBlurEffect-double-boolean-}
```
public final IBlur addBlurEffect(double radius, boolean grow)
```


Adiciona o novo efeito Blur ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| radius | double | O raio do desfoque. |
| grow | boolean | Especifica se os limites do objeto devem ser ampliados como resultado do desfoque. True indica que os limites são ampliados, enquanto false indica que não são. |

**Retorna:**
[IBlur](../../com.aspose.slides/iblur) - Índice do novo efeito de imagem na coleção.
### addColorChangeEffect() {#addColorChangeEffect--}
```
public final IColorChange addColorChangeEffect()
```


Adiciona o novo efeito Color Change ao final de uma coleção.

**Retorna:**
[IColorChange](../../com.aspose.slides/icolorchange) - Índice do novo efeito de imagem na coleção.
### addColorReplaceEffect() {#addColorReplaceEffect--}
```
public final IColorReplace addColorReplaceEffect()
```


Adiciona o novo efeito Color Replacement ao final de uma coleção.

**Retorna:**
[IColorReplace](../../com.aspose.slides/icolorreplace) - Índice do novo efeito de imagem na coleção.
### addDuotoneEffect() {#addDuotoneEffect--}
```
public final IDuotone addDuotoneEffect()
```


Adiciona o novo efeito Duotone ao final de uma coleção.

**Retorna:**
[IDuotone](../../com.aspose.slides/iduotone) - Índice do novo efeito de imagem na coleção.
### addFillOverlayEffect() {#addFillOverlayEffect--}
```
public final IFillOverlay addFillOverlayEffect()
```


Adiciona o novo efeito Fill Overlay ao final de uma coleção.

**Retorna:**
[IFillOverlay](../../com.aspose.slides/ifilloverlay) - Índice do novo efeito de imagem na coleção.
### addGrayScaleEffect() {#addGrayScaleEffect--}
```
public final IGrayScale addGrayScaleEffect()
```


Adiciona o novo efeito Gray Scale ao final de uma coleção.

**Retorna:**
[IGrayScale](../../com.aspose.slides/igrayscale) - Índice do novo efeito de imagem na coleção.
### addHSLEffect(float hue, float saturation, float luminance) {#addHSLEffect-float-float-float-}
```
public final IHSL addHSLEffect(float hue, float saturation, float luminance)
```


Adiciona o novo efeito Hue/Saturation/Luminance ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | O número de graus pelos quais o matiz é ajustado. |
| saturation | float | A porcentagem pela qual a saturação é ajustada. |
| luminance | float | A porcentagem pela qual a luminância é ajustada. |

**Retorna:**
[IHSL](../../com.aspose.slides/ihsl) - Índice do novo efeito de imagem na coleção.
### addLuminanceEffect(float brightness, float contrast) {#addLuminanceEffect-float-float-}
```
public final ILuminance addLuminanceEffect(float brightness, float contrast)
```


Adiciona o novo efeito Luminance ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brightness | float | A porcentagem para alterar o brilho. |
| contrast | float | A porcentagem para alterar o contraste. |

**Retorna:**
[ILuminance](../../com.aspose.slides/iluminance) - Índice do novo efeito de imagem na coleção.
### addTintEffect(float hue, float amount) {#addTintEffect-float-float-}
```
public final ITint addTintEffect(float hue, float amount)
```


Adiciona o novo efeito Tint ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hue | float | O matiz para o qual aplicar o tinte. |
| amount | float | Especifica o quanto o valor da cor é deslocado. |

**Retorna:**
[ITint](../../com.aspose.slides/itint) - Índice do novo efeito de imagem na coleção.
### addBrightnessContrastEffect(float brightness, float contrast) {#addBrightnessContrastEffect-float-float-}
```
public final IBrightnessContrast addBrightnessContrastEffect(float brightness, float contrast)
```


Adiciona o novo efeito BrightnessContrast ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| brightness | float | A porcentagem para alterar o brilho. |
| contrast | float | A porcentagem para alterar o contraste. |

**Retorna:**
[IBrightnessContrast](../../com.aspose.slides/ibrightnesscontrast) - Índice do novo efeito de imagem na coleção.
### size() {#size--}
```
public final int size()
```


Retorna o número de efeitos de imagem em uma coleção. Somente leitura int.

**Retorna:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Obtém um valor indicando se o [IGenericCollection](../../com.aspose.slides/igenericcollection) é somente leitura. Somente leitura boolean.

**Retorna:**
boolean - true se o [IGenericCollection](../../com.aspose.slides/igenericcollection) for somente leitura; caso contrário, false.
### addItem(IImageTransformOperation operation) {#addItem-com.aspose.slides.IImageTransformOperation-}
```
public final void addItem(IImageTransformOperation operation)
```


Adiciona o novo efeito de imagem ao final de uma coleção.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| operation | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | O efeito de imagem a ser adicionado ao final de uma coleção. |

### clear() {#clear--}
```
public final void clear()
```


Remove todos os efeitos de imagem de uma coleção.

### containsItem(IImageTransformOperation item) {#containsItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean containsItem(IImageTransformOperation item)
```


Determina se o [IGenericCollection](../../com.aspose.slides/igenericcollection) contém um valor específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | O objeto a ser localizado no [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - true se o item for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, false.
### copyToTArray(IImageTransformOperation[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IImageTransformOperation---int-}
```
public final void copyToTArray(IImageTransformOperation[] array, int arrayIndex)
```


Copia os elementos do [IGenericCollection](../../com.aspose.slides/igenericcollection) para um Array, começando em um índice de Array específico.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | [IImageTransformOperation\[\]](../../com.aspose.slides/iimagetransformoperation) | O Array unidimensional que é o destino dos elementos copiados de [IGenericCollection](../../com.aspose.slides/igenericcollection). O Array deve ter indexação baseada em zero. |
| arrayIndex | int | O índice baseado em zero no array onde a cópia começa. |

### removeItem(IImageTransformOperation item) {#removeItem-com.aspose.slides.IImageTransformOperation-}
```
public final boolean removeItem(IImageTransformOperation item)
```


Remove a primeira ocorrência de um objeto específico do [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| item | [IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation) | O objeto a ser removido do [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Retorna:**
boolean - true se o item for removido com sucesso do [IGenericCollection](../../com.aspose.slides/igenericcollection); caso contrário, false. Este método também retorna false se o item não for encontrado no [IGenericCollection](../../com.aspose.slides/igenericcollection) original.
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IImageTransformOperation> iteratorJava()
```


Retorna um iterator java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IImageTransformOperation> - Um java.util.Iterator para a coleção inteira.