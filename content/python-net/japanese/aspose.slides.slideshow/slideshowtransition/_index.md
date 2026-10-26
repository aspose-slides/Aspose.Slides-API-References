---
title: SlideShowTransition class
second_title: Aspose.Slides for Python via .NET API リファレンス
description: 
type: docs
url: /ja/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition クラス

スライドショー遷移を表します。

SlideShowTransition 型は以下のメンバーを公開します。

## プロパティ

| Property | Description |
| :- | :- |
| [`sound`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/sound/) | 埋め込みオーディオデータを取得または設定します。<br/>            読み書き [`IAudio`](/slides/python-net/ja/aspose.slides/iaudio). |
| [`sound_mode`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/sound_mode/) | スライド遷移のサウンドモードを設定または取得します。<br/>            読み書き [`TransitionSoundMode`](/slides/python-net/ja/aspose.slides.slideshow/transitionsoundmode). |
| [`sound_loop`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/sound_loop/) | この属性は、次のサウンドイベントがスライドショー内で発生するまでサウンドをループさせるかどうかを指定します。<br/>            読み書き **bool**. |
| [`advance_on_click`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/advance_on_click/) | マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が設定されているとみなされます。<br/>            読み書き **bool**. |
| [`advance_after`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/advance_after/) | この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。<br/>            読み書き **bool**. |
| [`advance_after_time`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/advance_after_time/) | 遷移が開始されるまでの時間（ミリ秒）を指定します。この設定は advClick 属性と組み合わせて使用できます。この属性が指定されていない場合、自動進行は行われないものとみなされます。<br/>            読み書き **int**. |
| [`speed`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/speed/) | 現在のスライドから次のスライドへ遷移する際に使用する遷移速度を指定します。<br/>            読み書き [`TransitionSpeed`](/slides/python-net/ja/aspose.slides.slideshow/transitionspeed). |
| [`value`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/value/) | スライドショー遷移の値。<br/>            読み取り専用 [`ITransitionValueBase`](/slides/python-net/ja/aspose.slides.slideshow/itransitionvaluebase). |
| [`type`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/type/) | 遷移のタイプ。<br/>            読み書き [`TransitionType`](/slides/python-net/ja/aspose.slides.slideshow/transitiontype). |
| [`sound_is_built_in`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/sound_is_built_in/) | このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストでこのサウンドに指定された name 属性をチェックするよう通知され、必要に応じてカスタム名や UI を表示できます。<br/>            読み書き **bool**. |
| [`sound_name`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/sound_name/) | 遷移サウンドの人間が読みやすい名前を指定します。サウンド名を取得または設定するには [`SlideShowTransition.sound`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/sound) プロパティを割り当てる必要があります。<br/>            読み書き **str**. |
| [`duration`](/slides/python-net/ja/aspose.slides.slideshow/slideshowtransition/duration/) | スライド遷移効果の時間（ミリ秒）を取得または設定します。<br/>            読み書き **int**. |

### 参照
* モジュール [`aspose.slides.slideshow`](/slides/python-net/ja/aspose.slides.slideshow)
* ライブラリ [`Aspose.Slides`](/slides/python-net)