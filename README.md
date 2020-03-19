# template_github-action_js-type
 JavaScriptタイプのGitHubアクションのひな型

## 使うときは
* cloneしてリポートリポジトリの設定を変更するか、ファイルを移動・設置
* `.github/workflows/main.yml`のアクションリポジトリの指定部分を作成したリポジトリに変更

## trace from [JavaScript アクションを作成する](https://help.github.com/ja/actions/building-actions/creating-a-javascript-action)

## Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

### Inputs

#### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

### Outputs

#### `time`

The time we greeted you.

### Example usage

```yaml
uses: actions/hello-world-javascript-action@v1
with:
  who-to-greet: 'Mona the Octocat'
```

`uses`フィールドのリポジトリ名は作成したリポジトリに書き換えて使用