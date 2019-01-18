## Caching Notes 
Refer to [parent](:note:358de5b2-7a31-4165-a560-0241fcad8520) for the master list of items that are currently being worked on.

Caching is still a concern. Allegis would like to know more about caching concerns like how it works, if it can be managed/controlled, what effects it may have on performance, etc.

There are a couple things to check on immediately 
1. [Caching Data with Storable Actions](https://developer.salesforce.com/blogs/developer-relations/2017/03/lightning-components-best-practices-caching-data-storable-actions.html) discusses caching data when using the Lightning Data Service and Cacheable Server Actions. 
2. Discover where chaching is explicitly used in pages that are causing issues such as [Talent Landing Page](https://allegisgroup--load.lightning.force.com/lightning/r/Contact/0031p00001WvZ8LAAV/view). 
3. Get with Rajeesh to sync on the spike they did on [Lightning Web Components](https://developer.salesforce.com/blogs/2018/12/introducing-lightning-web-components.html) to see if there are practical components that effect caching positively or negatively.  
Refer to other strategies like [paging](https://developer.salesforce.com/blogs/developer-relations/2017/04/lightning-components-performance-best-practices.html#data_caching).
