# MockDatastoreService
A mirror of a older version of MockDatastoreService by Crazyman32, but compatible with legacy versions of Roblox.
#	USAGE EXAMPLE:
```
local dataStoreService = game:GetService("DataStoreService")
-- Mock service if the game is offline:
if (game.PlaceId == 0) then
	dataStoreService = require(game.ServerStorage.MockDataStoreService)
end
-- dataStoreService will act exactly like the real one
```
#	NOTE:
		This has been created based off of the DataStoreService on
		August 20, 2014. If a change has been made to the service,
		this mocked version will not reflect the changes.
