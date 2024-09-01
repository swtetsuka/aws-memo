AWS Global Accelerator

# よくある質問 より
https://aws.amazon.com/jp/global-accelerator/faqs/ より

- 静的 IP アドレスが提供される
- エッジロケーションからのエニーキャスト
- AWS Global Accelerator が提供する静的 IP アドレスを、Network Load Balancer、Application Load Balancer、EC2 インスタンス、Elastic IP アドレスなどのリージョン別 AWS リソースまたはエンドポイントに関連付ける
- エンドポイントグループのトラフィックダイヤルの割合を設定して、特定の AWS リージョンのトラフィックをトラフィックを調整する
- エンドポイント全体に重みを割り当てることによって、エンドポイントグループ内の各エンドポイントに割り当てられるトラフィック割合を制御する
- Amazon グローバルネットワーク
- 最初のバイトのレイテンシー (パケットがクライアントからエンドポイントに行き来する往復時間) とジッター (レイテンシーの変動) を低減
- 速度比較ツール https://speedtest.globalaccelerator.aws/#/
- グローバルクライアントベースを対象としたワークロードがある場合は、AWS Global Accelerator を使用を推奨
- ワークロードが単一の AWS リージョンでホストされ、AWS リージョン内およびその周辺でクライアントによって使用されている場合は、ELB

# 料金 より
https://aws.amazon.com/jp/global-accelerator/pricing/
- 1 時間 (1 時間未満は繰上げ) 毎: 0.025 USD
- 送信元と送信先が共にアジアパシフィック: 0.010 USD/GB

# 参考
- よくある質問 https://aws.amazon.com/jp/global-accelerator/faqs/
- AWS Global Accelerator Speed Comparison (速度比較ツール)  https://speedtest.globalaccelerator.aws/#/
- 料金 https://aws.amazon.com/jp/global-accelerator/pricing/

以上