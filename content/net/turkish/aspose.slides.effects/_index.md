---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes for .NET API Referansı
description: Microsoft PowerPoint sunumlarında çeşitli efektlerle çalışmak için sınıfları içerir.
type: docs
weight: 60
url: /tr/aspose.slides.effects/
---
Microsoft PowerPoint sunumlarında çeşitli efektlerle çalışmak için sınıfları içerir.

## Sınıflar

| Sınıf | Açıklama |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Eşiğin altında kalan Alpha (Opaklık) değerleri 0'a (tamamen şeffaf) değiştirilir ve eşiğin eşit veya üzerindeki alpha değerleri %100'e (tamamen opak) değiştirilir. |
| [AlphaCeiling](./alphaceiling) | Alpha (opaklık) değerleri sıfırdan büyük olduğu durumlarda %100'e değiştirilir. Başka bir deyişle, kısmen opak olan her şey tamamen opak olur. |
| [AlphaFloor](./alphafloor) | Alpha (opaklık) değerleri %100'ün altında olduğunda sıfıra (0) değiştirilir. Başka bir deyişle, kısmen saydam olan her şey tamamen şeffaf olur. |
| [AlphaInverse](./alphainverse) | Alpha (opaklık) değerleri %100'den çıkarılarak tersine çevrilir. |
| [AlphaModulate](./alphamodulate) | Etki alpha (opaklık) değerleri sabit bir yüzdeyle çarpılır. Etki kapsayıcısı, modüle edilecek alpha değerlerini içeren bir etkiyi belirtir. |
| [AlphaModulateFixed](./alphamodulatefixed) | Etki alpha (opaklık) değerleri sabit bir yüzdeyle çarpılır. |
| [AlphaReplace](./alphareplace) | Etki alpha (opaklık) değerleri sabit bir alpha ile değiştirilir. |
| [BiLevel](./bilevel) | Belirtilen eşik değerinden düşük parlaklığa (luminance) sahip giriş renkleri siyaha dönüştürülür. Parlaklığı eşik değerine eşit veya daha yüksek olan giriş renkleri beyaza ayarlanır. Alpha etki değerleri bu etki tarafından etkilenmez. |
| [Blur](./blur) | Tam şekle, dolgu dahil, uygulanan bir Bulanıklaştırma etkisini temsil eder. Alpha dahil tüm renk kanalları etkilenir. |
| [BrightnessContrast](./brightnesscontrast) | Parlaklık ve Kontrast etkisini temsil eder. Parlaklık ve kontrastı ayarlar |
| [ColorChange](./colorchange) | Renk Değiştirme etkisini temsil eder. FromColor örnekleri ToColor örnekleriyle değiştirilir. |
| [ColorReplace](./colorreplace) | Renk Değiştirme etkisini temsil eder. Tüm etki renkleri sabit bir renk ile değiştirilir. Alpha değerleri etkilenmez. |
| [Duotone](./duotone) | Duotone etkisini temsil eder. Her piksel için, Color1 ve Color2 lineer bir enterpolasyonla birleştirerek yeni rengi belirler. |
| [EffectFactory](./effectfactory) | Etkileri oluşturmayı sağlar |
| [FillOverlay](./filloverlay) | Doldurma Kaplaması etkisini temsil eder. Bir doldurma kaplaması, bir nesne için ek bir doldurma belirlemek ve iki doldurmayı birleştirmek için kullanılabilir. |
| [Glow](./glow) | Parıltı etkisini temsil eder; nesnenin kenarları dışında renkli bir bulanık dış hat eklenir. |
| [GrayScale](./grayscale) | Gri Ölçek etkisini temsil eder. Tüm etki renk değerlerini parlaklıklarına karşılık gelen bir gri tonuna dönüştürür. Etki alpha (opaklık) değerleri etkilenmez. |
| [HSL](./hsl) | Hue/Doygunluk/Parlaklık etkisini temsil eder. Renk tonu, doygunluk ve parlaklık, mevcut değerlerine göre ayarlanabilir. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | Etkili görüntü dönüşüm etkilerinin salt okunur bir koleksiyonunu temsil eden değiştirilemez nesne. |
| [ImageTransformOperation](./imagetransformoperation) | Soyut görüntü dönüşüm etkisini temsil eder. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | Bir görüntüye uygulanan etkilerin koleksiyonunu temsil eder. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | Görüntü dönüşüm işlemlerini oluşturmayı sağlar |
| [InnerShadow](./innershadow) | İç Gölge etkisini temsil eder. |
| [Luminance](./luminance) | Parlaklık, tüm renkleri lineer olarak beyaza veya siyaha yaklaştırır. Kontrast, tüm renkleri birbirine daha yakın veya daha uzak olacak şekilde ölçeklendirir. |
| [OuterShadow](./outershadow) | Dış Gölge etkisini temsil eder. |
| [PresetShadow](./presetshadow) | Ön tanımlı Gölge etkisini temsil eder. |
| [Reflection](./reflection) | Yansıma etkisini temsil eder. |
| [SoftEdge](./softedge) | Şeklin kenarları bulanıklaştırılır, ancak dolgu etkilenmez. |
| [Tint](./tint) | Tint etkisini temsil eder. Etki renk değerlerini belirtilen miktarda renk tonuna doğru/ters yönde kaydırır. |

## Arayüzler

| Arayüz | Açıklama |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Eşiğin altında kalan Alpha (Opaklık) değerleri 0'a (tamamen şeffaf) değiştirilir ve eşiğin eşit veya üzerindeki alpha değerleri %100'e (tamamen opak) değiştirilir. |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Alpha (Opaklık) değerleri 0'a (tamamen şeffaf) ve eşiğin eşit ya da üzerindeki alpha değerleri %100'e (tamamen opak) değiştirilir. Değiştirilemez nesne. |
| [IAlphaCeiling](./ialphaceiling) | Alpha (opaklık) değerleri sıfırdan büyük olduğu durumlarda %100'e değiştirilir. Başka bir deyişle, kısmen opak olan her şey tamamen opak olur. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Alpha (opaklık) değerleri sıfırdan büyük olduğu durumlarda %100'e değiştirilir. Başka bir deyişle, kısmen opak olan her şey tamamen opak olur. Değiştirilemez nesne. |
| [IAlphaFloor](./ialphafloor) | Alpha (opaklık) değerleri %100'ün altında olduğunda sıfıra (0) değiştirilir. Başka bir deyişle, kısmen saydam olan her şey tamamen şeffaf olur. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Alpha (opaklık) değerleri %100'ün altında olduğunda sıfıra (0) değiştirilir. Başka bir deyişle, kısmen saydam olan her şey tamamen şeffaf olur. Değiştirilemez nesne. |
| [IAlphaInverse](./ialphainverse) | Alpha (opaklık) değerleri %100'den çıkarılarak tersine çevrilir. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Alpha (opaklık) değerleri %100'den çıkarılarak tersine çevrilir. Değiştirilemez nesne. |
| [IAlphaModulate](./ialphamodulate) | Etki alpha (opaklık) değerleri sabit bir yüzdeyle çarpılır. Etki kapsayıcısı, modüle edilecek alpha değerlerini içeren bir etkiyi belirtir. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Etki alpha (opaklık) değerleri sabit bir yüzdeyle çarpılır. Etki kapsayıcısı, modüle edilecek alpha değerlerini içeren bir etkiyi belirtir. Değiştirilemez nesne. |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Etki alpha (opaklık) değerleri sabit bir yüzdeyle çarpılır. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Etki alpha (opaklık) değerleri sabit bir yüzdeyle çarpılır. Değiştirilemez nesne. |
| [IAlphaReplace](./ialphareplace) | Temel IImageTransformOperation arayüzünü temsil eder. |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Alpha Replace etkisini temsil eden değiştirilemez nesne. Etki alpha (opaklık) değerleri sabit bir alpha ile değiştirilir. |
| [IBiLevel](./ibilevel) | Temel IImageTransformOperation arayüzünü temsil eder. |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Bi-Level (siyah/beyaz) etkisini temsil eden değiştirilemez nesne. Parlaklığı belirtilen eşik değerinden düşük giriş renkleri siyaha döner, eşik değere eşit veya yüksek giriş renkleri beyaza ayarlanır. Alpha etki değerleri etkilenmez. |
| [IBlur](./iblur) | Tam şekle, dolgu dahil, uygulanan bir Bulanıklaştırma etkisini temsil eder. Alpha dahil tüm renk kanalları etkilenir. |
| [IBlurEffectiveData](./iblureffectivedata) | Tam şekle, dolgu dahil, uygulanan bir Bulanıklaştırma etkisini temsil eder. Alpha dahil tüm renk kanalları etkilenir. Değiştirilemez nesne. |
| [IBrightnessContrast](./ibrightnesscontrast) | Parlaklık ve Kontrast etkisini temsil eder. Parlaklık ve kontrastı ayarlar |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | Parlaklık ve Kontrast etkisini temsil eder. Parlaklık ve kontrastı ayarlar. Değiştirilemez nesne. |
| [IColorChange](./icolorchange) | Renk Değiştirme etkisini temsil eder. FromColor örnekleri ToColor örnekleriyle değiştirilir. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Renk Değiştirme etkisini temsil eder. FromColor örnekleri ToColor örnekleriyle değiştirilir. Değiştirilemez nesne. |
| [IColorReplace](./icolorreplace) | Renk Değiştirme etkisini temsil eder. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Renk Değiştirme etkisini temsil eder. Tüm etki renkleri sabit bir renk ile değiştirilir. Alpha değerleri etkilenmez. Değiştirilemez nesne. |
| [IDuotone](./iduotone) | Duotone etkisini temsil eder. |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Duotone etkisini temsil eden değiştirilemez nesne. Her piksel için, clr1 ve clr2 lineer bir enterpolasyonla birleştirerek yeni rengi belirler. |
| [IEffectEffectiveData](./ieffecteffectivedata) | Etkiyi temsil eden değiştirilemez nesneler için temel sınıf. |
| [IEffectFactory](./ieffectfactory) | Etkilerin örneklerini oluşturmayı sağlar |
| [IFillOverlay](./ifilloverlay) | Doldurma Kaplaması etkisini temsil eder. Bir doldurma kaplaması, bir nesne için ek bir doldurma belirlemek ve iki doldurmayı birleştirmek için kullanılabilir. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Doldurma Kaplaması etkisini temsil eden değiştirilemez nesne. Bir doldurma kaplaması, bir nesne için ek bir doldurma belirlemek ve iki doldurmayı birleştirmek için kullanılabilir. |
| [IGlow](./iglow) | Parıltı etkisini temsil eder; nesnenin kenarları dışında renkli bir bulanık dış hat eklenir. |
| [IGlowEffectiveData](./igloweffectivedata) | Parıltı etkisini temsil eden değiştirilemez nesne; nesnenin kenarları dışında renkli bir bulanık dış hat eklenir. |
| [IGrayScale](./igrayscale) | IImageTransformOperation arayüzünü temsil eder. |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Gray Scale etkisini temsil eden değiştirilemez nesne. Tüm etki renk değerlerini parlaklıklarına karşılık gelen bir gri tonuna dönüştürür. Etki alpha (opaklık) değerleri etkilenmez. |
| [IHSL](./ihsl) | Hue/Doygunluk/Parlaklık etkisini temsil eder. Renk tonu, doygunluk ve parlaklık, mevcut değerlerine göre ayarlanabilir. |
| [IHSLEffectiveData](./ihsleffectivedata) | Hue/Doygunluk/Parlaklık etkisini temsil eder. Renk tonu, doygunluk ve parlaklık, mevcut değerlerine göre ayarlanabilir. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | Etkili görüntü dönüşüm etkilerinin salt okunur bir koleksiyonunu temsil eden değiştirilemez nesne. |
| [IImageTransformOperation](./iimagetransformoperation) | Soyut görüntü dönüşüm etkisini temsil eder. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | Bir görüntüye uygulanan etkilerin koleksiyonunu temsil eder. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | Görüntü etkilerinin örneklerini oluşturmayı sağlar |
| [IInnerShadow](./iinnershadow) | İç gölge etkisini temsil eder. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | İç gölge etkisini temsil eden değiştirilemez nesne. |
| [ILuminance](./iluminance) | Parlaklık, tüm renkleri lineer olarak beyaza veya siyaha yaklaştırır. Kontrast, tüm renkleri birbirine daha yakın veya daha uzak olacak şekilde ölçeklendirir. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Parlaklık, tüm renkleri lineer olarak beyaza veya siyaha yaklaştırır. Kontrast, tüm renkleri birbirine daha yakın veya daha uzak olacak şekilde ölçeklendirir. |
| [IOuterShadow](./ioutershadow) | Dış Gölge etkisini temsil eder. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Dış Gölge etkisini temsil eden değiştirilemez nesne. |
| [IPresetShadow](./ipresetshadow) | Ön tanımlı Gölge etkisini temsil eder. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Ön tanımlı Gölge etkisini temsil eden değiştirilemez nesne. |
| [IReflection](./ireflection) | Yansıma etkisini temsil eder. |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Yansıma etkisini temsil eden değiştirilemez nesne. |
| [ISoftEdge](./isoftedge) | Soft Edge etkisini temsil eder. Şeklin kenarları bulanıklaştırılır, ancak dolgu etkilenmez. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Soft Edge etkisini temsil eden değiştirilemez nesne. Şeklin kenarları bulanıklaştırılır, ancak dolgu etkilenmez. |
| [ITint](./itint) | Tint etkisini temsil eder. Etki renk değerlerini belirtilen miktarda renk tonuna doğru/ters yönde kaydırır. |
| [ITintEffectiveData](./itinteffectivedata) | Tint etkisini temsil eden değiştirilemez nesne. Etki renk değerlerini belirtilen miktarda renk tonuna doğru/ters yönde kaydırır. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->