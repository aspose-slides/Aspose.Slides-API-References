---
title: ISlideShowTransition class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides/islideshowtransition/
---
## ISlideShowTransition クラス

スライドショー遷移を表します。

ISlideShowTransition 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/ja/aspose.slides/islideshowtransition/sound/) | 埋め込みオーディオデータを取得または設定します。<br/>            読み取り/書き込み [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio)。 |
| [`sound_mode`](/slides/python-net/ja/aspose.slides/islideshowtransition/sound_mode/) | スライド遷移のサウンドモードを設定または取得します。<br/>            読み取り/書き込み [`TransitionSoundMode`](/slides/python-net/ja/aspose.slides.slideshow/transitionsoundmode)。 |
| [`sound_loop`](/slides/python-net/ja/aspose.slides/islideshowtransition/sound_loop/) | この属性は、サウンドが次のサウンドイベントが発生するまでループするかどうかを指定します。<br/>            スライドショーで。<br/>            読み取り/書き込み **bool**。 |
| [`advance_on_click`](/slides/python-net/ja/aspose.slides/islideshowtransition/advance_on_click/) | マウスクリックでスライドを進めるかどうかを指定します。<br/>            この属性が指定されていない場合、true が前提とされます。<br/>            読み取り/書き込み **bool**。 |
| [`advance_after`](/slides/python-net/ja/aspose.slides/islideshowtransition/advance_after/) | この属性は、スライドショーが一定時間後に次のスライドに移動するかどうかを指定します。<br/>            読み取り/書き込み **bool**。 |
| [`advance_after_time`](/slides/python-net/ja/aspose.slides/islideshowtransition/advance_after_time/) | 遷移が開始すべき時間をミリ秒で指定します。この設定<br/>            advClick 属性と組み合わせて使用できます。この属性が指定されていない<br/>            場合、自動進行が行われないとみなされます。<br/>            読み取り/書き込み **int**。 |
| [`speed`](/slides/python-net/ja/aspose.slides/islideshowtransition/speed/) | 現在のスライドから次のスライドへの遷移に使用される遷移速度を指定します。<br/>            読み取り/書き込み [`TransitionSpeed`](/slides/python-net/ja/aspose.slides.slideshow/transitionspeed)。 |
| [`value`](/slides/python-net/ja/aspose.slides/islideshowtransition/value/) | スライドショー遷移の値。<br/>            読み取り専用 [`ITransitionValueBase`](/slides/python-net/ja/aspose.slides.slideshow/itransitionvaluebase)。 |
| [`type`](/slides/python-net/ja/aspose.slides/islideshowtransition/type/) | 遷移の種類。<br/>            読み取り/書き込み [`TransitionType`](/slides/python-net/ja/aspose.slides.slideshow/transitiontype)。 |
| [`sound_is_built_in`](/slides/python-net/ja/aspose.slides/islideshowtransition/sound_is_built_in/) | このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションはこのサウンドに指定された name 属性を組み込みサウンドのリストでチェックするよう通知され、必要に応じてカスタム名や UI を表示できます。<br/>            読み取り/書き込み **bool**。 |
| [`sound_name`](/slides/python-net/ja/aspose.slides/islideshowtransition/sound_name/) | 遷移サウンドの人間が読める名前を指定します。[`ISlideShowTransition.sound`](/slides/python-net/ja/aspose.slides/islideshowtransition/sound) プロパティに割り当てることでサウンド名の取得または設定が可能です。<br/>            読み取り/書き込み **str**。 |
| [`duration`](/slides/python-net/ja/aspose.slides/islideshowtransition/duration/) | スライド遷移効果の継続時間をミリ秒で取得または設定します。<br/>            読み取り/書き込み **int**。 |

### 参照
* モジュール [`aspose.slides`](/slides/python-net/ja/aspose.slides)
* ライブラリ [`Aspose.Slides`](/slides/python-net)