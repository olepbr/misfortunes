# Misfortunes

A collection of quotes. I use them for email signatures; you can use them for
whatever you like.

## Usage

I leverage `fortune` to pick quotes at random. For that to work, you need to
feed the file to `strfile`, i.e. `strfile misfortunes`. Finally, to get a
random quote, you call `fortune misfortunes`.

A script for generating an email signature can then be as simple as:

```bash
echo 'Name Nameson'
fortune "<path-to-misfortunes>"
```

## TODO

- [ ] Store the quotes in an SQLite database so that they can be attributed
  properly. (*I* know where they're from, but you might want to, too.)
