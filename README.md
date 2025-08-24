# Lavalink on Railway
- Dockerベース / v4
- YouTubeはプラグインで有効化

## Env
- PORT=2333
- SERVER_PORT=2333
- LAVALINK_SERVER_PASSWORD=<強い値>
- LAVALINK_PLUGINS_0_DEPENDENCY=dev.lavalink.youtube:youtube-plugin:1.13.3
- LAVALINK_PLUGINS_0_REPOSITORY=https://maven.lavalink.dev/releases
- _JAVA_OPTIONS=-Xmx512m (任意)

## Healthcheck
GET /version （Authorization: <password> ヘッダ）
