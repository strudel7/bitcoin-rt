## bitcoin-rt

A clone of http://bitcoinmonitor.com using WebSockets instead of long polling
and [d3][] instead of jQuery UI. The idea is to visualize all transactions
in the global [Bitcoin][] network. If you don't know what Bitcoin is, or don't
know much about it, you should watch this [two minute video][video].

The intention is to render trade data from all major exchanges as well as all
account-to-account transfers and block creation events from the blockchain.
The UI should eventually allow users to determine via a slider the date range
they wish to see, hover for detailed transaction data, and ideally provide a
[Google-finance][] style set of checkboxes allowing the user to include/exclude
which kinds of transactions they wish to see, which exchanges, etc.

A number of functionally equivalent implementations are available in the various
sub-directories including Node.js, Node.js with SockJS, Tomcat-based Servlet,
vert.x, and Atmosphere. See the README files in each for setup instructions.

[d3]: http://d3js.org
[bitcoin]: http://bitcoin.org
[video]: http://www.weusecoins.com
[mtgox]: https://mtgox.com
[google-finance]: http://www.google.com/finance
