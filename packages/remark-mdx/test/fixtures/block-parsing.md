# [Block parsing](https://github.com/mdx-js/mdx/issues/195)

From [GitHub](https://github.com/mdx-js/mdx/issues/195#issuecomment-506745859).

<Row>
  <Col>
  - some md
  - asd
  - asd
  </Col>
  <Col>
  **some md**
  </Col>
</Row>

From [GitHub](https://github.com/mdx-js/mdx/issues/195#issuecomment-507167800)

<Col>

- osm
- <Icon name="hero" /> **This will be plain text, not MD**
- **some md**

</Col>

A couple from [John](https://github.com/mdx-js/mdx/issues/195#issuecomment-613509708):

# Hello, world!

<Foo
  stuff={`
Here is a template literal

with an empty line
  `}
/>

# Hello, <>{props.name}</>

Weeeeee!

# Hello, world!

<Foo>
  {
    <h2>{1+1}</h2>
  }
</Foo>
