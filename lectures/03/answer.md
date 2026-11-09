# 第3回 解答

## 演習

- 第1回（素のLLM）とエージェントの回答の違い：
- `--trace` で見えたツール呼び出し（ツール名と引数）：search_glossary({'query': 'LoRA QLoRA'})
- 1つの質問での LLM 呼び出し回数（`requests`）：2回が1回になった。
- 追加したツールと、docstring に書いた説明：query には調べたい用語をまとめて入れる

## 宿題

- 取り組んだレベル：基礎
- やったこと：docstring の「用語を1つだけ入れる」を「まとめて入れる」に変更
- 結果：[tool call]   search_glossaryの回数が一回となった。
- 気づき・疑問：
