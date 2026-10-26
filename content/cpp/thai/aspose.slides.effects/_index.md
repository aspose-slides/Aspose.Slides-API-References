---
title: "Aspose::Slides::Effects"
second_title: อ้างอิง API Aspose.Slides สำหรับ C++
description: 
type: docs
weight: 66
url: /th/aspose.slides.effects/
---
## คลาส

| คลาส | คำอธิบาย |
| --- | --- |
| [AlphaBiLevel](./alphabilevel/) | แสดงถึงเอฟเฟกต์ Alpha Bi-Level. ค่า Alpha (Opacity) ที่น้อยกว่าค่าที่กำหนดจะถูกเปลี่ยนเป็น 0 (โปร่งใสเต็ม) และค่า alpha ที่มากกว่าหรือเท่ากับค่าที่กำหนดจะถูกเปลี่ยนเป็น 100% (ทึบเต็ม). |
| [AlphaCeiling](./alphaceiling/) | แสดงถึงเอฟเฟกต์ Alpha Ceiling. ค่า Alpha (opacity) ที่มากกว่า 0 จะถูกเปลี่ยนเป็น 100%. กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นทึบเต็ม. |
| [AlphaFloor](./alphafloor/) | แสดงถึงเอฟเฟกต์ Alpha Floor. ค่า Alpha (opacity) ที่น้อยกว่า 100% จะถูกเปลี่ยนเป็น 0. กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นโปร่งใสเต็ม. |
| [AlphaInverse](./alphainverse/) | แสดงถึงเอฟเฟกต์ Alpha Inverse. ค่า Alpha (opacity) จะถูกกลับโดยการลบจาก 100%. |
| [AlphaModulate](./alphamodulate/) | แสดงถึงเอฟเฟกต์ Alpha Modulate. ค่าเอฟเฟกต์ alpha (opacity) จะถูกคูณด้วยเปอร์เซ็นต์คงที่. ตัวคอนเทนเนอร์ของเอฟเฟกต์ระบุเอฟเฟกต์ที่มีค่า alpha เพื่อทำการโมดูลูต. |
| [AlphaModulateFixed](./alphamodulatefixed/) | แสดงถึงเอฟเฟกต์ Alpha Modulate Fixed. ค่าเอฟเฟกต์ alpha (opacity) จะถูกคูณด้วยเปอร์เซ็นต์คงที่. |
| [AlphaReplace](./alphareplace/) | แสดงถึงเอฟเฟกต์ Alpha Replace. ค่าเอฟเฟกต์ alpha (opacity) จะถูกแทนที่ด้วยค่า alpha คงที่. |
| [BiLevel](./bilevel/) | แสดงถึงเอฟเฟกต์ Bi-Level (สีดำ/ขาว). สีอินพุตที่ความสว่างน้อยกว่าค่าที่กำหนดจะถูกเปลี่ยนเป็นสีดำ. สีอินพุตที่ความสว่างมากกว่าหรือเท่ากับค่าที่กำหนดจะถูกตั้งเป็นสีขาว. ค่าของเอฟเฟกต์ alpha จะไม่ถูกกระทบโดยเอฟเฟกต์นี้. |
| [Blur](./blur/) | แสดงถึงเอฟเฟกต์ [Blur](./blur/) ที่ถูกนำไปใช้กับรูปร่างทั้งหมดรวมถึงการเติม. ทุกช่องสีรวมถึง alpha จะได้รับผลกระทบ. |
| [BrightnessContrast](./brightnesscontrast/) | แสดงถึงเอฟเฟกต์ [BrightnessContrast](./brightnesscontrast/). ปรับความสว่างและความคอนทราสต์ |
| [ColorChange](./colorchange/) | แสดงถึงเอฟเฟกต์ Color Change. อินสแตนซ์ของ FromColor จะถูกแทนที่ด้วยอินสแตนซ์ของ ToColor. |
| [ColorReplace](./colorreplace/) | แสดงถึงเอฟเฟกต์ Color Replacement. สีเอฟเฟกต์ทั้งหมดจะถูกเปลี่ยนเป็นสีคงที่. ค่า Alpha จะไม่ถูกกระทบ. |
| [Duotone](./duotone/) | แสดงถึงเอฟเฟกต์ [Duotone](./duotone/). สำหรับแต่ละพิกเซล จะรวม Color1 และ Color2 ผ่านการเชิงเส้นเพื่อกำหนดสีใหม่สำหรับพิกเซลนั้น. |
| [EffectFactory](./effectfactory/) | อนุญาตให้สร้างเอฟเฟกต์ |
| [FillOverlay](./filloverlay/) | แสดงถึงเอฟเฟกต์ Fill Overlay. Fill overlay สามารถใช้ระบุการเติมเพิ่มเติมสำหรับออบเจกต์และผสานการเติมทั้งสองเข้าด้วยกัน. |
| [Glow](./glow/) | แสดงถึงเอฟเฟกต์ [Glow](./glow/) ที่เส้นขอบสีเบลอถูกเพิ่มอยู่ด้านนอกของวัตถุ. |
| [GrayScale](./grayscale/) | แสดงถึงเอฟเฟกต์ Gray Scale. แปลงค่าของสีเอฟเฟกต์ทั้งหมดให้เป็นเฉดสีเทาตามความสว่างของมัน. ค่าเอฟเฟกต์ alpha (opacity) จะไม่ถูกกระทบ. |
| [HSL](./hsl/) | แสดงถึงเอฟเฟกต์ Hue/Saturation/Luminance. ความสี, ความอิ่มสี, และความสว่างสามารถปรับได้แต่ละค่าโดยอิงจากค่าปัจจุบัน. |
| [IAlphaBiLevel](./ialphabilevel/) | แสดงถึงเอฟเฟกต์ Alpha Bi-Level. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Bi-Level. Alpha (Opacity) values less than the threshold are changed to 0 (fully transparent) and alpha values greater than or equal to the threshold are changed to 100% (fully opaque). |
| [IAlphaCeiling](./ialphaceiling/) | แสดงถึงเอฟเฟกต์ Alpha Ceiling. Alpha (opacity) values greater than zero are changed to 100%. กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นทึบเต็ม. |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Ceiling. Alpha (opacity) values greater than zero are changed to 100%. กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นทึบเต็ม. |
| [IAlphaFloor](./ialphafloor/) | แสดงถึงเอฟเฟกต์ Alpha Floor. Alpha (opacity) values less than 100% are changed to zero. กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นโปร่งใสเต็ม. |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Floor. Alpha (opacity) values less than 100% are changed to zero. กล่าวคือ สิ่งที่โปร่งใสบางส่วนจะกลายเป็นโปร่งใสเต็ม. |
| [IAlphaInverse](./ialphainverse/) | แสดงถึงเอฟเฟกต์ Alpha Inverse. Alpha (opacity) values are inverted by subtracting from 100%. |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Inverse. Alpha (opacity) values are inverted by subtracting from 100%. |
| [IAlphaModulate](./ialphamodulate/) | แสดงถึงเอฟเฟกต์ Alpha Modulate. ค่าเอฟเฟกต์ alpha (opacity) จะถูกคูณด้วยเปอร์เซ็นต์คงที่. ตัวคอนเทนเนอร์ของเอฟเฟกต์ระบุเอฟเฟกต์ที่มีค่า alpha เพื่อทำการโมดูลูต. |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Modulate. ค่าเอฟเฟกต์ alpha (opacity) จะถูกคูณด้วยเปอร์เซ็นต์คงที่. ตัวคอนเทนเนอร์ของเอฟเฟกต์ระบุเอฟเฟกต์ที่มีค่า alpha เพื่อทำการโมดูลูต. |
| [IAlphaModulateFixed](./ialphamodulatefixed/) | แสดงถึงเอฟเฟกต์ Alpha Modulate Fixed. ค่าเอฟเฟกต์ alpha (opacity) จะถูกคูณด้วยเปอร์เซ็นต์คงที่. |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Modulate Fixed. ค่าเอฟเฟกต์ alpha (opacity) จะถูกคูณด้วยเปอร์เซ็นต์คงที่. |
| [IAlphaReplace](./ialphareplace/) | แสดงถึงอินเทอร์เฟซพื้นฐาน [IImageTransformOperation](./iimagetransformoperation/). |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Alpha Replace. ค่าเอฟเฟกต์ alpha (opacity) จะถูกแทนที่ด้วยค่า alpha คงที่. |
| [IApplicableEffect](./iapplicableeffect/) |  |
| [IBiLevel](./ibilevel/) | แสดงถึงอินเทอร์เฟซพื้นฐาน [IImageTransformOperation](./iimagetransformoperation/). |
| [IBiLevelEffectiveData](./ibileveleffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Bi-Level (สีดำ/ขาว). สีอินพุตที่ความสว่างน้อยกว่าค่าที่กำหนดจะถูกเปลี่ยนเป็นสีดำ. สีอินพุตที่ความสว่างมากกว่าหรือเท่ากับค่าที่กำหนดจะถูกตั้งเป็นสีขาว. ค่าของเอฟเฟกต์ alpha จะไม่ถูกกระทบโดยเอฟเฟกต์นี้. |
| [IBlur](./iblur/) | แสดงถึงเอฟเฟกต์ [Blur](./blur/) ที่ถูกนำไปใช้กับรูปร่างทั้งหมดรวมถึงการเติม. ทุกช่องสีรวมถึง alpha จะได้รับผลกระทบ. |
| [IBlurEffectiveData](./iblureffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ [Blur](./blur/) ที่ถูกนำไปใช้กับรูปร่างทั้งหมดรวมถึงการเติม. ทุกช่องสีรวมถึง alpha จะได้รับผลกระทบ. |
| [IBrightnessContrast](./ibrightnesscontrast/) | แสดงถึงเอฟเฟกต์ [BrightnessContrast](./brightnesscontrast/). ปรับความสว่างและความคอนทราสต์ |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ [BrightnessContrast](./brightnesscontrast/). ปรับความสว่างและความคอนทราสต์ |
| [IColorChange](./icolorchange/) | แสดงถึงเอฟเฟกต์ Color Change. อินสแตนซ์ของ FromColor จะถูกแทนที่ด้วยอินสแตนซ์ของ ToColor. |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Color Change. อินสแตนซ์ของ FromColor จะถูกแทนที่ด้วยอินสแตนซ์ของ ToColor. |
| [IColorReplace](./icolorreplace/) | แสดงถึงเอฟเฟกต์ Color Replacement. |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Color Replacement. สีเอฟเฟกต์ทั้งหมดจะถูกเปลี่ยนเป็นสีคงที่. ค่า Alpha จะไม่ถูกกระทบ. |
| [IDuotone](./iduotone/) | แสดงถึงเอฟเฟกต์ [Duotone](./duotone/). |
| [IDuotoneEffectiveData](./iduotoneeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ [Duotone](./duotone/). สำหรับแต่ละพิกเซล จะรวม clr1 และ clr2 ผ่านการเชิงเส้นเพื่อกำหนดสีใหม่สำหรับพิกเซลนั้น. |
| [IEffectEffectiveData](./ieffecteffectivedata/) | คลาสฐานสำหรับอ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์. |
| [IEffectFactory](./ieffectfactory/) | อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์ |
| [IFillOverlay](./ifilloverlay/) | แสดงถึงเอฟเฟกต์ Fill Overlay. Fill overlay สามารถใช้ระบุการเติมเพิ่มเติมสำหรับออบเจกต์และผสานการเติมทั้งสองเข้าด้วยกัน. |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Fill Overlay. Fill overlay สามารถใช้ระบุการเติมเพิ่มเติมสำหรับออบเจกต์และผสานการเติมทั้งสองเข้าด้วยกัน. |
| [IGlow](./iglow/) | แสดงถึงเอฟเฟกต์ [Glow](./glow/) ที่เส้นขอบสีเบลอถูกเพิ่มอยู่ด้านนอกของวัตถุ. |
| [IGlowEffectiveData](./igloweffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ [Glow](./glow/) ที่เส้นขอบสีเบลอถูกเพิ่มอยู่ด้านนอกของวัตถุ. |
| [IGrayScale](./igrayscale/) | แสดงถึงอินเทอร์เฟซ [IImageTransformOperation](./iimagetransformoperation/). |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Gray Scale. แปลงค่าของสีเอฟเฟกต์ทั้งหมดให้เป็นเฉดสีเทาตามความสว่างของมัน. ค่าเอฟเฟกต์ alpha (opacity) จะไม่ถูกกระทบ. |
| [IHSL](./ihsl/) | แสดงถึงเอฟเฟกต์ Hue/Saturation/Luminance. ความสี, ความอิ่มสี, และความสว่างสามารถปรับได้แต่ละค่าโดยอิงจากค่าปัจจุบัน. |
| [IHSLEffectiveData](./ihsleffectivedata/) | แสดงถึงเอฟเฟกต์ Hue/Saturation/Luminance. ความสี, ความอิ่มสี, และความสว่างสามารถปรับได้แต่ละค่าโดยอิงจากค่าปัจจุบัน. |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งเป็นคอลเลกชันแบบ readonly ของเอฟเฟกต์การแปลงภาพที่มีประสิทธิภาพ. |
| [IImageTransformOperation](./iimagetransformoperation/) | แสดงถึงเอฟเฟกต์การแปลงภาพแบบแอ็บสแตร็กต์. |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection/) | แสดงถึงคอลเลกชันของเอฟเฟกต์ที่นำไปใช้กับภาพ. |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory/) | อนุญาตให้สร้างอินสแตนซ์ของเอฟเฟกต์ภาพ |
| [IInnerShadow](./iinnershadow/) | แสดงถึงเอฟเฟกต์ inner shadow. |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ inner shadow. |
| [ILuminance](./iluminance/) | แสดงถึงเอฟเฟกต์ [Luminance](./luminance/). ความสว่างทำให้สีทั้งหมดเลื่อนเชิงเส้นเข้าหาแสงหรือความมืด. คอนทราสต์ทำให้สีทั้งหมดห่างหรือใกล้กันมากขึ้น. |
| [ILuminanceEffectiveData](./iluminanceeffectivedata/) | แสดงถึงเอฟเฟกต์ [Luminance](./luminance/). ความสว่างทำให้สีทั้งหมดเลื่อนเชิงเส้นเข้าหาแสงหรือความมืด. คอนทราสต์ทำให้สีทั้งหมดห่างหรือใกล้กันมากขึ้น. |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งเป็นคอลเลกชันแบบ readonly ของเอฟเฟกต์การแปลงภาพที่มีประสิทธิภาพ. |
| [ImageTransformOperation](./imagetransformoperation/) | แสดงถึงเอฟเฟกต์การแปลงภาพแบบแอ็บสแตร็กต์. |
| [ImageTransformOperationCollection](./imagetransformoperationcollection/) | แสดงถึงคอลเลกชันของเอฟเฟกต์ที่นำไปใช้กับภาพ. |
| [ImageTransformOperationFactory](./imagetransformoperationfactory/) | อนุญาตให้สร้างการดำเนินการแปลงภาพ |
| [InnerShadow](./innershadow/) | แสดงถึงเอฟเฟกต์ Inner Shadow. |
| [IOuterShadow](./ioutershadow/) | แสดงถึงเอฟเฟกต์ Outer Shadow. |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Outer Shadow. |
| [IPresetShadow](./ipresetshadow/) | แสดงถึงเอฟเฟกต์ Preset Shadow. |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ Preset Shadow. |
| [IReflection](./ireflection/) | แสดงถึงเอฟเฟกต์ reflection. |
| [IReflectionEffectiveData](./ireflectioneffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ [Reflection](./reflection/). |
| [ISoftEdge](./isoftedge/) | แสดงถึงเอฟเฟกต์ Soft Edge. ขอบของรูปร่างจะเบลอ, แต่การเติมจะไม่ถูกกระทบ. |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ soft edge. ขอบของรูปร่างจะเบลอ, แต่การเติมจะไม่ถูกกระทบ. |
| [ITint](./itint/) | แสดงถึงเอฟเฟกต์ [Tint](./tint/). เปลี่ยนค่าของสีเอฟเฟกต์ให้เข้า/ออกจาก hue ตามจำนวนที่ระบุ. |
| [ITintEffectiveData](./itinteffectivedata/) | อ็อบเจกต์ที่ไม่สามารถแก้ไขได้ซึ่งแสดงถึงเอฟเฟกต์ [Tint](./tint/). เปลี่ยนค่าของสีเอฟเฟกต์ให้เข้า/ออกจาก hue ตามจำนวนที่ระบุ. |
| [IVisualEffect](./ivisualeffect/) |  |
| [Luminance](./luminance/) | แสดงถึงเอฟเฟกต์ [Luminance](./luminance/). ความสว่างทำให้สีทั้งหมดเลื่อนเชิงเส้นเข้าหาแสงหรือความมืด. คอนทราสต์ทำให้สีทั้งหมดห่างหรือใกล้กันมากขึ้น. |
| [OuterShadow](./outershadow/) | แสดงถึงเอฟเฟกต์ Outer Shadow. |
| [PresetShadow](./presetshadow/) | แสดงถึงเอฟเฟกต์ Preset Shadow. |
| [Reflection](./reflection/) | แสดงถึงเอฟเฟกต์ [Reflection](./reflection/). |
| [SoftEdge](./softedge/) | แสดงถึงเอฟเฟกต์ soft edge. ขอบของรูปร่างจะเบลอ, แต่การเติมจะไม่ถูกกระทบ. |
| [Tint](./tint/) | แสดงถึงเอฟเฟกต์ [Tint](./tint/). เปลี่ยนค่าของสีเอฟเฟกต์ให้เข้า/ออกจาก hue ตามจำนวนที่ระบุ. |