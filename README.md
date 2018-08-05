# DownloadHash
Etheruem Smart Contract to maintain Download Hash for multi-owner files.

**Note**: It is not suggested that Etherueme is the best choise for implementing this software.

Downloading Hashes are used to verify the downloaded file is original and not been tampered.

The problem is that Download Hashes are usually stored on a website which makes it a SPOF (jargon, read it as Single Point of Failure).

The idea is to provide an alternative way to maintain the source of truth for the Download Hash that does not have that vulnerability.

In this example, we are using Etheruem Smart Contract to allow file owners to maintain the Download Hash.
