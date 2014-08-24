doorbell-
=========

...	...	@@ -19,6 +19,8 @@ typedef NS_ENUM(NSInteger, MemState) {
19	19	 + (NSMutableDictionary*) pointers;
20	20	 
21	21	 + (BOOL) track:(NSObject *)obj;
22	++ (BOOL) untrack:(NSObject *)obj;
23	+
22	24	 
23	25	 + (BOOL) wipe:(NSObject *)obj;
24	26	 + (BOOL) wipeAll;
