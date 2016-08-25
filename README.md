"# PhoenixProject" 

１．PostgreSQLがいるらしい(9.5.4を入れた)
https://www.postgresql.org/download/windows/
http://www.enterprisedb.com/products-services-training/pgdownload#windows
Version 9.5.4 Win x86-64

２．pgAdmin IIIアプリを使って、接続ユーザとデータベースを作成した

３．Phoenixフレームワークの設定
config/dev.exs

# Configure your database
config :phoenix_server, PhoenixServer.Repo,
  adapter: Ecto.Adapters.Postgres,
  ・・・