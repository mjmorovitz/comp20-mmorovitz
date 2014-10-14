This project fails to get and parse data from MBTA API. This is because client side Java must obey the Same Origin Policy. This means that since my page does not originate from the same site as the MBTA API, I am prevented from accessing their data. This is why a status code of "0" is displayed when I make an xmlhttp request for data. 

The google map rendered is of Boston MA. This project took approximately 3 hours to complete (before I realized it could not be done).
