---
title: ColorTransformOperation enumeration
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/colortransformoperation/
---
## ColorTransformOperation 列挙型

カラー変換操作を定義します。

ColorTransformOperation 型は次のメンバーを公開します。

## フィールド

| フィールド | 説明 |
| :- | :- |
| TINT | 色に色調を付けます。パラメーターは 0（元の色）から 1（白）までの範囲です。 |
| SHADE | 色をシェーディングします。パラメーターは 0（元の色）から 1（黒）までの範囲です。 |
| COMPLEMENT | 色を RGB の補色に変換します。<br/>            m = Max(r, g, b);<br/>            r = m - r;<br/>            g = m - g;<br/>            b = m - b; |
| INVERSE | 色を反転色に変換します。<br/>            r = 1 - r;<br/>            g = 1 - g;<br/>            b = 1 - b; |
| GRAYSCALE | 色を同じ明度の灰色に変換します。パラメーターは無視されます。 |
| SET_ALPHA | 色のアルファ成分を定義します。パラメーターは 0（透明）から 1（不透明）までの範囲です。 |
| ADD_ALPHA | パラメーターの値を色のアルファ成分に加算します。パラメーターは -1 から 1 の範囲です。 |
| MULTIPLY_ALPHA | アルファ成分にパラメーターの値を掛けます。 |
| SET_HUE | 色相成分をパラメーターの値に変更します。パラメーターは 0 から 360 の範囲です。 |
| ADD_HUE | パラメーターの値を色相成分に加算します。パラメーターは -360 から 360 の範囲です。 |
| MULTIPLY_HUE | 色相成分にパラメーターの値を掛けます。 |
| SET_SATURATION | 彩度成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。 |
| ADD_SATURATION | パラメーターの値を彩度成分に加算します。パラメーターは -1 から 1 の範囲です。 |
| MULTIPLY_SATURATION | 彩度成分にパラメーターの値を掛けます。 |
| SET_LUMINANCE | 輝度成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。 |
| ADD_LUMINANCE | パラメーターの値を輝度成分に加算します。パラメーターは -1 から 1 の範囲です。 |
| MULTIPLY_LUMINANCE | 輝度成分にパラメーターの値を掛けます。 |
| SET_RED | 赤色成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。 |
| ADD_RED | パラメーターの値を赤色成分に加算します。パラメーターは -1 から 1 の範囲です。 |
| MULTIPLY_RED | 赤色成分にパラメーターを掛けます。 |
| SET_GREEN | 緑色成分をパラメーターの値に変更します。パラメーターは 0 から 1 の範囲です。 |
| ADD_GREEN | パラメーターを緑色成分に加算します。パラメーターは -1 から 1 の範囲です。 |
| MULTIPLY_GREEN | 緑色成分にパラメーターの値を掛けます。 |
| SET_BLUE | 青色成分をパラメーターの値に変更します。パラメーターは 0 から 360 の範囲です。 |
| ADD_BLUE | パラメーターの値を青色成分に加算します。パラメーターは -1 から 1 の範囲です。 |
| MULTIPLY_BLUE | 青色成分にパラメーターの値を掛けます。 |
| GAMMA | ガンマ補正。パラメーターは無視されます。 |
| INVERSE_GAMMA | 逆ガンマ補正。パラメーターは無視されます。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)