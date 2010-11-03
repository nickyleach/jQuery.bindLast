# jQuery.bindLast
`jQuery.bindLast` helps you add *some* order to event binding in jQuery. Events bound using `jQuery.bindLast()` are ensured to be executed after those events bound by the vanilla `jQuery.bind()`.

The syntax is similar to `jQuery.bind()` with the exception that the `eventData` parameter is not currently supported. In other words:

`.bind( eventType, handler(eventObject) )`
***
__eventType__ A string containing one or more JavaScript event types, such as "click" or "submit," or custom event names.  
__handler(eventObject)__ A function to execute each time the event is triggered.

Events bound using `bindLast` are __not__ guaranteed to run in any particular order, so in this way it behaves similarly to `bind`.