## Installation

Your email client must support Sieve filters. Consult your email client's
documentation for instructions on installing them.

Because these filters move emails into an email folder named _Filtered out_, you
may need to create an email folder named _Filtered out_ before the filters will
work. I don't know whether email programs typically create the folder
automatically.

## Filters

The following Sieve email filters are provided by this project:

| Filter                                                        | Description                                                                                 |
| ------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| [Feedback requests](./filters/feedback-requests/filter.sieve) | Filters out emails which request feedback: "rate your trip," "tell us what you think," etc. |
| [Terms of Service](./filters/terms-of-service/filter.sieve)   | Filters out emails about terms of service updates, privacy policy changes, and the like.    |

## False positives and false negatives

No email filter is perfect. False positives (filtering out emails you _want_ to
see) and false negatives (_not_ filtering out emails you _don't_ want to see)
will occur. Desperate attempts to _know what you think_ and to tell you that
_something changed_ will still get through from time to time. Even still, the
filters will be improved over time. Just keep an eye on the _Filtered out_ email
folder, especially if you're waiting for an important email or having trouble
finding an email that you think you should have received.
