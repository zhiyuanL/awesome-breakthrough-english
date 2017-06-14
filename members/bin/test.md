1. After some investigation, I found the cause of this issue is the values of *received-date* and *sent-date** are inconsistent: we are using *received-date* as date value when click "Inbox" folder, and using the other when click "Send" folder, they are both from "msgheaderlist" Webtop API. I suggest talking with Webtop developer, and reach an agreement to choose one for it.

2. Hi Chetan Kandhare,  
The tests you gave are based on original design drawing, but they have some unreasonable places and functional conflict, therefore after discussing with Jake, I just modified its color and layout as designed, and buttons is remained.
Contrast figures as follows: