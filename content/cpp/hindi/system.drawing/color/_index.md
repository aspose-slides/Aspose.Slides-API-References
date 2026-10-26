---
title: Color
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: "एक रंग को दर्शाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 53
url: /hi/system.drawing/color/
---
## रंग क्लास

रंग को दर्शाता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और मान या संदर्भ द्वारा फ़ंक्शन को पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../../system/smartptr/) क्लास का उपयोग न करें।

```cpp
class Color
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
|  [Color](./color/)() | एक \"खाली\" इंस्टेंस बनाता है [Color](./) क्लास का, जो किसी भी रंग का प्रतिनिधित्व नहीं करता। |
| **bool** [Equals](./equals/)(const [Color](./)\&) const | निर्धारित करता है कि वर्तमान और निर्दिष्ट [Color](./) वस्तुएँ एक ही रंग का प्रतिनिधित्व करती हैं या नहीं। |
| static [Color](./) [FromArgb](./fromargb/)(int) | एक इंस्टेंस बनाता है [Color](./) क्लास का, जो निर्दिष्ट रंग का प्रतिनिधित्व करता है। |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int, int) | एक इंस्टेंस बनाता है [Color](./) क्लास का, जो निर्दिष्ट रंग का प्रतिनिधित्व करता है। |
| static [Color](./) [FromArgb](./fromargb/)(int, int, int) | एक इंस्टेंस बनाता है [Color](./) क्लास का, जिसका अल्फा घटक 0xFF पर सेट होता है। |
| static [Color](./) [FromArgb](./fromargb/)(int, [Color](./)) | एक इंस्टेंस बनाता है [Color](./) क्लास का, जो निर्दिष्ट रंग का प्रतिनिधित्व करता है। |
| static [Color](./) [FromKnownColor](./fromknowncolor/)([KnownColor](../knowncolor/)) | एक इंस्टेंस बनाता है [Color](./) क्लास का, जो निर्दिष्ट ज्ञात रंग का प्रतिनिधित्व करता है। |
| static [Color](./) [FromName](./fromname/)(const [String](../../system/string/)\&) | एक इंस्टेंस बनाता है [Color](./) क्लास का, जो निर्दिष्ट नाम वाले रंग का प्रतिनिधित्व करता है। |
| int [get_A](./get_a/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के अल्फा घटक का मान लौटाता है। |
| static [Color](./) [get_AliceBlue](./get_aliceblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF0F8FF। |
| static [Color](./) [get_AntiqueWhite](./get_antiquewhite/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFAEBD7। |
| static [Color](./) [get_Aqua](./get_aqua/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00FFFF। |
| static [Color](./) [get_Aquamarine](./get_aquamarine/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF7FFFD4। |
| static [Color](./) [get_Azure](./get_azure/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF0FFFF। |
| int [get_B](./get_b/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के ब्लू घटक का मान लौटाता है। |
| static [Color](./) [get_Beige](./get_beige/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF5F5DC। |
| static [Color](./) [get_Bisque](./get_bisque/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFE4C4। |
| static [Color](./) [get_Black](./get_black/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF000000। |
| static [Color](./) [get_BlanchedAlmond](./get_blanchedalmond/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFEBCD। |
| static [Color](./) [get_Blue](./get_blue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF0000FF। |
| static [Color](./) [get_BlueViolet](./get_blueviolet/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF8A2BE2। |
| static [Color](./) [get_Brown](./get_brown/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFA52A2A। |
| static [Color](./) [get_BurlyWood](./get_burlywood/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDEB887। |
| static [Color](./) [get_CadetBlue](./get_cadetblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF5F9EA0। |
| static [Color](./) [get_Chartreuse](./get_chartreuse/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF7FFF00। |
| static [Color](./) [get_Chocolate](./get_chocolate/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFD2691E। |
| static [Color](./) [get_Coral](./get_coral/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF7F50। |
| static [Color](./) [get_CornflowerBlue](./get_cornflowerblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF6495ED। |
| static [Color](./) [get_Cornsilk](./get_cornsilk/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFF8DC। |
| static [Color](./) [get_Crimson](./get_crimson/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDC143C। |
| static [Color](./) [get_Cyan](./get_cyan/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00FFFF। |
| static [Color](./) [get_DarkBlue](./get_darkblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00008B। |
| static [Color](./) [get_DarkCyan](./get_darkcyan/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF008B8B। |
| static [Color](./) [get_DarkGoldenrod](./get_darkgoldenrod/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFB8860B। |
| static [Color](./) [get_DarkGray](./get_darkgray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFA9A9A9। |
| static [Color](./) [get_DarkGreen](./get_darkgreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF006400। |
| static [Color](./) [get_DarkKhaki](./get_darkkhaki/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFBDB76B। |
| static [Color](./) [get_DarkMagenta](./get_darkmagenta/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF8B008B। |
| static [Color](./) [get_DarkOliveGreen](./get_darkolivegreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF556B2F। |
| static [Color](./) [get_DarkOrange](./get_darkorange/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF8C00। |
| static [Color](./) [get_DarkOrchid](./get_darkorchid/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF9932CC। |
| static [Color](./) [get_DarkRed](./get_darkred/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF8B0000। |
| static [Color](./) [get_DarkSalmon](./get_darksalmon/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFE9967A। |
| static [Color](./) [get_DarkSeaGreen](./get_darkseagreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF8FBC8F। |
| static [Color](./) [get_DarkSlateBlue](./get_darkslateblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF483D8B। |
| static [Color](./) [get_DarkSlateGray](./get_darkslategray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF2F4F4F। |
| static [Color](./) [get_DarkTurquoise](./get_darkturquoise/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00CED1। |
| static [Color](./) [get_DarkViolet](./get_darkviolet/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF9400D3। |
| static [Color](./) [get_DeepPink](./get_deeppink/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF1493। |
| static [Color](./) [get_DeepSkyBlue](./get_deepskyblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00BFFF। |
| static [Color](./) [get_DimGray](./get_dimgray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF696969। |
| static [Color](./) [get_DodgerBlue](./get_dodgerblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF1E90FF। |
| static [Color](./) [get_Firebrick](./get_firebrick/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFB22222। |
| static [Color](./) [get_FloralWhite](./get_floralwhite/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFAF0। |
| static [Color](./) [get_ForestGreen](./get_forestgreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF228B22। |
| static [Color](./) [get_Fuchsia](./get_fuchsia/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF00FF। |
| int [get_G](./get_g/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के ग्रीन घटक का मान लौटाता है। |
| static [Color](./) [get_Gainsboro](./get_gainsboro/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDCDCDC। |
| static [Color](./) [get_GhostWhite](./get_ghostwhite/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF8F8FF। |
| static [Color](./) [get_Gold](./get_gold/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFD700। |
| static [Color](./) [get_Goldenrod](./get_goldenrod/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDAA520। |
| static [Color](./) [get_Gray](./get_gray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF808080। |
| static [Color](./) [get_Green](./get_green/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF008000। |
| static [Color](./) [get_GreenYellow](./get_greenyellow/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFADFF2F। |
| static [Color](./) [get_Honeydew](./get_honeydew/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF0FFF0। |
| static [Color](./) [get_HotPink](./get_hotpink/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF69B4। |
| static [Color](./) [get_IndianRed](./get_indianred/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFCD5C5C। |
| static [Color](./) [get_Indigo](./get_indigo/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF4B0082। |
| **bool** [get_IsEmpty](./get_isempty/)() const | एक मान लौटाता है जो संकेत करता है कि वर्तमान वस्तु \"खाली\" है, अर्थात् कोई रंग प्रतिनिधित्व नहीं करती। |
| **bool** [get_IsNamedColor](./get_isnamedcolor/)() const | एक मान लौटाता है जो निर्धारित करता है कि [Color](./) संरचना एक नामित रंग है या KnownColor अंकन का सदस्य। |
| static [Color](./) [get_Ivory](./get_ivory/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFFF0। |
| static [Color](./) [get_Khaki](./get_khaki/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF0E68C। |
| static [Color](./) [get_Lavender](./get_lavender/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFE6E6FA। |
| static [Color](./) [get_LavenderBlush](./get_lavenderblush/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFF0F5। |
| static [Color](./) [get_LawnGreen](./get_lawngreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF7CFC00। |
| static [Color](./) [get_LemonChiffon](./get_lemonchiffon/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFACD। |
| static [Color](./) [get_LightBlue](./get_lightblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFADD8E6। |
| static [Color](./) [get_LightCoral](./get_lightcoral/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF08080। |
| static [Color](./) [get_LightCyan](./get_lightcyan/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFE0FFFF। |
| static [Color](./) [get_LightGoldenrodYellow](./get_lightgoldenrodyellow/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFAFAD2। |
| static [Color](./) [get_LightGray](./get_lightgray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFD3D3D3। |
| static [Color](./) [get_LightGreen](./get_lightgreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF90EE90। |
| static [Color](./) [get_LightPink](./get_lightpink/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFB6C1। |
| static [Color](./) [get_LightSalmon](./get_lightsalmon/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFA07A। |
| static [Color](./) [get_LightSeaGreen](./get_lightseagreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF20B2AA। |
| static [Color](./) [get_LightSkyBlue](./get_lightskyblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF87CEFA। |
| static [Color](./) [get_LightSlateGray](./get_lightslategray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF778899। |
| static [Color](./) [get_LightSteelBlue](./get_lightsteelblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFB0C4DE। |
| static [Color](./) [get_LightYellow](./get_lightyellow/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFFE0। |
| static [Color](./) [get_Lime](./get_lime/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00FF00। |
| static [Color](./) [get_LimeGreen](./get_limegreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF32CD32। |
| static [Color](./) [get_Linen](./get_linen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFAF0E6। |
| static [Color](./) [get_Magenta](./get_magenta/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF00FF। |
| static [Color](./) [get_Maroon](./get_maroon/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF800000। |
| static [Color](./) [get_MediumAquamarine](./get_mediumaquamarine/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF66CDAA। |
| static [Color](./) [get_MediumBlue](./get_mediumblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF0000CD। |
| static [Color](./) [get_MediumOrchid](./get_mediumorchid/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFBA55D3। |
| static [Color](./) [get_MediumPurple](./get_mediumpurple/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF9370DB। |
| static [Color](./) [get_MediumSeaGreen](./get_mediumseagreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF3CB371। |
| static [Color](./) [get_MediumSlateBlue](./get_mediumslateblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF7B68EE। |
| static [Color](./) [get_MediumSpringGreen](./get_mediumspringgreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00FA9A। |
| static [Color](./) [get_MediumTurquoise](./get_mediumturquoise/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF48D1CC। |
| static [Color](./) [get_MediumVioletRed](./get_mediumvioletred/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFC71585। |
| static [Color](./) [get_MidnightBlue](./get_midnightblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF191970। |
| static [Color](./) [get_MintCream](./get_mintcream/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF5FFFA। |
| static [Color](./) [get_MistyRose](./get_mistyrose/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFE4E1। |
| static [Color](./) [get_Moccasin](./get_moccasin/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFE4B5। |
| [String](../../system/string/) [get_Name](./get_name/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग का नाम लौटाता है। |
| static [Color](./) [get_NavajoWhite](./get_navajowhite/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFDEAD। |
| static [Color](./) [get_Navy](./get_navy/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF000080। |
| static [Color](./) [get_OldLace](./get_oldlace/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFDF5E6। |
| static [Color](./) [get_Olive](./get_olive/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF808000। |
| static [Color](./) [get_OliveDrab](./get_olivedrab/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF6B8E23। |
| static [Color](./) [get_Orange](./get_orange/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFA500। |
| static [Color](./) [get_OrangeRed](./get_orangered/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF4500। |
| static [Color](./) [get_Orchid](./get_orchid/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDA70D6। |
| static [Color](./) [get_PaleGoldenrod](./get_palegoldenrod/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFEEE8AA। |
| static [Color](./) [get_PaleGreen](./get_palegreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF98FB98। |
| static [Color](./) [get_PaleTurquoise](./get_paleturquoise/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFAFEEEE। |
| static [Color](./) [get_PaleVioletRed](./get_palevioletred/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDB7093। |
| static [Color](./) [get_PapayaWhip](./get_papayawhip/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFEFD5। |
| static [Color](./) [get_PeachPuff](./get_peachpuff/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFDAB9। |
| static [Color](./) [get_Peru](./get_peru/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFCD853F। |
| static [Color](./) [get_Pink](./get_pink/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFC0CB। |
| static [Color](./) [get_Plum](./get_plum/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFDDA0DD। |
| static [Color](./) [get_PowderBlue](./get_powderblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFB0E0E6। |
| static [Color](./) [get_Purple](./get_purple/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF800080। |
| int [get_R](./get_r/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के रेड घटक का मान लौटाता है। |
| static [Color](./) [get_Red](./get_red/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF0000। |
| static [Color](./) [get_RosyBrown](./get_rosybrown/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFBC8F8F। |
| static [Color](./) [get_RoyalBlue](./get_royalblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF4169E1। |
| static [Color](./) [get_SaddleBrown](./get_saddlebrown/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF8B4513। |
| static [Color](./) [get_Salmon](./get_salmon/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFA8072। |
| static [Color](./) [get_SandyBrown](./get_sandybrown/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF4A460। |
| static [Color](./) [get_SeaGreen](./get_seagreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF2E8B57। |
| static [Color](./) [get_SeaShell](./get_seashell/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFF5EE। |
| static [Color](./) [get_Sienna](./get_sienna/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFA0522D। |
| static [Color](./) [get_Silver](./get_silver/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFC0C0C0। |
| static [Color](./) [get_SkyBlue](./get_skyblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF87CEEB। |
| static [Color](./) [get_SlateBlue](./get_slateblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF6A5ACD। |
| static [Color](./) [get_SlateGray](./get_slategray/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF708090। |
| static [Color](./) [get_Snow](./get_snow/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFAFA। |
| static [Color](./) [get_SpringGreen](./get_springgreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF00FF7F। |
| static [Color](./) [get_SteelBlue](./get_steelblue/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF4682B4। |
| static [Color](./) [get_Tan](./get_tan/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFD2B48C। |
| static [Color](./) [get_Teal](./get_teal/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF008080। |
| static [Color](./) [get_Thistle](./get_thistle/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFD8BFD8। |
| static [Color](./) [get_Tomato](./get_tomato/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFF6347। |
| static [Color](./) [get_Transparent](./get_transparent/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #00FFFFFF। |
| static [Color](./) [get_Turquoise](./get_turquoise/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF40E0D0। |
| static [Color](./) [get_Violet](./get_violet/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFEE82EE। |
| static [Color](./) [get_Wheat](./get_wheat/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF5DEB3। |
| static [Color](./) [get_White](./get_white/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFFFF। |
| static [Color](./) [get_WhiteSmoke](./get_whitesmoke/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFF5F5F5। |
| static [Color](./) [get_Yellow](./get_yellow/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FFFFFF00। |
| static [Color](./) [get_YellowGreen](./get_yellowgreen/)() | एक रंग लौटाता है जिसका ARGB मान हैक्साडेसिमल नोटेशन में #FF9ACD32। |
| **float** [GetBrightness](./getbrightness/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के ब्राइटनेस घटक को लौटाता है। |
| int [GetHashCode](./gethashcode/)() const | वर्तमान वस्तु का हैश कोड लौटाता है। |
| **float** [GetHue](./gethue/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के HSB hue मान को डिग्री में लौटाता है। |
| **float** [GetSaturation](./getsaturation/)() | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग के HSB संतृप्ति को लौटाता है। |
| **bool** [IsNull](./isnull/)() const | हमेशा false लौटाता है। |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | हमेशा true लौटाता है। |
| **bool** [operator!=](./operator_not_equal/)(const [Color](./)\&) const | निर्धारित करता है कि वर्तमान और निर्दिष्ट [Color](./) वस्तुएँ अलग-अलग रंगों का प्रतिनिधित्व करती हैं या नहीं। |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | हमेशा false लौटाता है। |
| **bool** [operator==](./operator_equal_equal/)(const [Color](./)\&) const | निर्धारित करता है कि वर्तमान और निर्दिष्ट [Color](./) वस्तुएँ एक ही रंग का प्रतिनिधित्व करती हैं या नहीं। |
| int [ToArgb](./toargb/)() const | वर्तमान वस्तु द्वारा प्रतिनिधित्व किए गए रंग का 32-बिट ARGB मान लौटाता है। |
| [String](../../system/string/) [ToString](./tostring/)() const | वर्तमान वस्तु का स्ट्रिंग प्रतिनिधित्व लौटाता है। |
## फ़ील्ड

| फ़ील्ड | विवरण |
| --- | --- |
| static [Empty](./empty/) | एक \"खाली\" इंस्टेंस [Color](./) क्लास का, अर्थात् एक इंस्टेंस जो किसी भी रंग का प्रतिनिधित्व नहीं करता। |
## देखें

* नामस्थान [System::Drawing](../)
* लाइब्रेरी [Aspose.Slides](../../)