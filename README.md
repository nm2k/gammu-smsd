# gammu-smsd scripts
Set of simple but useful bash scripts for gammu-smsd:
* gammu_wrapper: extracts SMS/ MMS messages from gammu's ENV variables. Returns timestamp, phone_number and message composed of single or multipple SMS/ MMS parts.
* /wrappers
	* psql_wrapper: extracts phone_number and message from Postgres instance. Returns timestamp, phone_number and message.
	* pushbullet_wrapper: initiates delivery of messages composed by gammu/ psql wrappers through bushbullet app.
	* telegram_wrapper: initiates delivery of messages composed by gammu/ psql wrappers through through telegram app.
* ping_if_alive: generates a ping using gammu-smsd-inject.
