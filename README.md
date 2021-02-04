# Speeding up your tethering by lying to your phone

> **Disclaimer**: *I am **not** responsible for **any** irresponsible, illegal, or immoral actions you might take. I am not an attorney and nothing in this repository should be construed as legal advice. Don't be evil, and don't run a server farm off your mobile hotspot.*

Most every road warrior, jetsetter, or coffee shop regular knows the limits their mobile hotspot. It's probably throttled by the carrier - that brand new 5G iPhone somehow only permits 5mbps or so.

But how does this work?

Your carrier is measuring the `ttl`, aka, the number of hops each packet makes in transit.

If your phone has a TTL of 64, of example, your tethered computer will have an incremented TTL of 65.

Fortunately, this TTl is just a piece of metadata built on trust.