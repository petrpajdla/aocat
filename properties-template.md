## has_identifier 

Domain:  
: [`AO_Entity`](classes.qmd#ao_entity)

Range:  
: `xsd:string`

Subproperty of:  
: *None*

Superproperty of:  
: *None*

Obligation:  
: Optional

Scope Note:  
: This property associates an ARIADNE entity with an identifier for that entity in some namespace other than the ARIADNE namespace (where the primary identifier of the entity belongs) and other than the provider’s namespace (which is associated to data resources by property `has_original_id`). 
The range of this property is `xsd:string` for generality.

Maps to:  
: `has_identifier` is a shortcut of the fully developed path `crm:P1_is_identified_by` → `crm:E42_Identifier`

Hints:  
: Values of `dct:identifier` can be used to compute the ARIADNE identifier.
