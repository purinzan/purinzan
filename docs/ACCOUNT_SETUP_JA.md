# GitHub アカウント整備メモ

## 現状

- GitHub login: `purinzan`
- profile repository: `purinzan/purinzan` は未作成
- public repositories: `my-app`, `tiktoker`, `video-gallery`
- private repositories: `us-stock-bot`
- `gh` CLI はこの環境では未導入

## まず作るもの

1. GitHub で public repository `purinzan/purinzan` を作る。
2. このフォルダの `README.md` と `assets/profile-banner.svg` を入れる。
3. default branch は `main`。
4. Repository description は次にする。

```text
GitHub profile README for local-first engineering tools.
```

## Profile Settings

GitHub の profile settings には以下のどれかを入れる。

Name:

```text
Purinzan
```

Bio:

```text
Building local-first tools for PLC analysis, factory automation, and AI-assisted engineering.
```

Shorter bio:

```text
Local-first PLC analysis and AI-assisted engineering tools.
```

Location:

```text
Japan
```

## Pinned Repositories

公開直後のおすすめ順:

1. `gx3-cli-mcp`
2. `video-gallery`
3. `tiktoker`

`my-app` は create-next-app の既定 README のままだったため、現状では pin しない。残すなら README と repository description を先に直す。

## Public Impression Checklist

- Profile README がある
- Avatar が暗い背景でも見やすい
- Bio が 1 行で何を作る人か伝える
- Pin する repo は README が既定テンプレのままではない
- 公開予定 repo に topics が入っている
- 機密データ、`.gx3`、`.db`、`.csv`、生成物が public repo に入っていない

