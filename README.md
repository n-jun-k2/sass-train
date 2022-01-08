# SASS の練習環境

練習環境の起動とログイン方法：
```bash
> docker-compose up -d && docker-compose exec node /bin/bash

root@40e7fe08a286:/app/src# npx gulp -v
CLI version: 2.3.0
Local version: 4.0.2
```

### sass のコンパイル
``/frontend/css``ディレクトリにコンパイル結果が格納される。
```bash
root@40e7fe08a286:/app/src# npm run build
```
