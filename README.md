## When doing engineering designs, we are assuming...

### Factoring Problem

* Assumption: It's hard to factorize a large integer to two primes.
* Or: RSA will be done.
* Mitigation: Post-quantom algorithms.

### Hashing algorithms like MD5/SHA-1

* Assumption: MD5/SHA-1 of two pieces of different data are different.
* Or: Potential of impersonation. (Check [SHAttered.io](https://shattered.io).)
* Mitigation: SHA-256 seems to be still okay.

### UUID

* Assumption: Generated UUIDs will not collapse.
* Or: Collision leads to confusion.
* Mitigation: Twitter's [Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake).

## License

CC BY-NC-SA 4.0
