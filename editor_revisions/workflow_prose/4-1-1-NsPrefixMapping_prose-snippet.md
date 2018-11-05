### 4.1.1 [Component NsPrefixMapping](#componentNsPrefixMapping)

The NsPrefixMapping component defines the mapping of namespace URIs to namespace prefixes. This is required to evaluate XPath expression when using transport syntaxes that don’t support namespace.

Below follows a list of the sub-components that MAY be present within this component:

« The NamespaceURI element SHALL contain one instance of a URI. » [DSS-4.1.1-1].

« The NamespacePrefix element SHALL contain one instance of a string. » [DSS-4.1.1-2].

#### 4.1.1.1 [NsPrefixMapping – JSON Syntax](#json_NsPrefixMapping)

« The NsPrefixMappingType JSON object SHALL implement in JSON syntax the requirements defined in the NsPrefixMapping component. » [JDSS-4.1.1.1-1].

« Properties of the JSON object SHALL implement the sub-components of NsPrefixMapping using JSON-specific names mapped as shown in the table below.

|| Element || Implementing JSON member name ||
| NamespaceURI | uri |
| NamespacePrefix | pre |

 » [JDSS-4.1.1.1-2]. The NsPrefixMappingType JSON object is defined in the JSON schema [[DSBJSON](#refDSBJSON)] and is provided below as a service to the reader.

```
$INSERT_JSON("dsb-NsPrefixMappingType")NOSJ_TRESNI$
```

#### 4.1.1.2 [NsPrefixMapping – XML Syntax](#xml_NsPrefixMapping)

« The XML type NsPrefixMappingType SHALL implement the requirements defined in the NsPrefixMapping component. » [XDSS-4.1.1.2-1].

The NsPrefixMappingType XML element is defined in XML Schema [[DSBXSD](#refDSBXSD)] and is provided below as a service to the reader.

```
$INSERT_XML("NsPrefixMappingType")LMX_TRESNI$
```

« Each child element of NsPrefixMappingType XML element SHALL implement in XML syntax the sub-component that has a name equal to its local name. » [XDSS-4.1.1.2-2].
