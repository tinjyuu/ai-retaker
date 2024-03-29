# ai-retaker

## 使い方
ai-retakerは下記のOSSの合成音声のモデルで音声合成を行います。

- [Style-Bert-VITS2](https://github.com/litagin02/Style-Bert-VITS2)
- [GPT-SoVITS](https://github.com/RVC-Boss/GPT-SoVITS)


### Style-Bert-VITS2のセットアップ

#### インストール
公式のREADMEを参考にStyle-Bert-VITS2のインストールを行います。  
[公式 README](https://github.com/litagin02/Style-Bert-VITS2)

#### モデルの配置
インストールが完了したら、Style-Bert-Vits2のディレクトリのmodel_assetsに、以下の手順でモデルをダウンロードして配置してください。
1. [tinjyuu/style-bert-vits2-siozawa](https://huggingface.co/tinjyuu/style-bert-vits2-siozawa/tree/main) のリポジトリにアクセスします。
2. リポジトリのページにアクセスし、siowazaディレクトリを選択します。
3. siowazaディレクトリ内のすべてのファイルを選択し、ダウンロードします。
4. ダウンロードしたsiowazaディレクトリを、Style-Bert-Vits2のディレクトリ内のmodel_assetsディレクトリに配置します。
以上の手順により、必要なモデルファイルがStyle-Bert-Vits2/model_assets/siowazaに配置されます。モデルの配置が完了したら、音声合成を実行する準備が整います。

```
Style-Bert-Vits2/
│
├── model_assets/
│   └── siowaza/
└── README.md
```

#### 音声合成
Style-Bert-VITS2のディレクトリのEditor.batをダブルクリックか、python server_editor.py --inbrowserを実行して音声合成のエディタを起動します。

起動したら、先程配置したモデルを選択し、テキスト欄に好きなテキストを入力して音声合成を行います。
文字を入力すると自動的に音声合成が行われ、音声が再生されます。

![Editor](images/sbv_editor.png)


## デモ

バーチャルハンサム
<video src="https://github.com/tinjyuu/ai-retaker/assets/8444525/cf3078c2-a5a1-48d4-90e0-e1636e99f22b" controls="controls" style="max-width: 730px;">
</video>

バーチャル美女
<video src="https://github.com/tinjyuu/ai-retaker/assets/8444525/813aad3f-03eb-4ea4-802e-af9f74ec430e" controls="controls" style="max-width: 730px;">
</video>


デモ動画
声優の塩沢兼人さん（故人）による生成ボイスのデモです。問題があれば削除します。

[![Image Alt Text](https://img.youtube.com/vi/un3xf7t5kJ8/0.jpg)](https://www.youtube.com/watch?v=un3xf7t5kJ8)
