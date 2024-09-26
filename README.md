# salcrom-Product-Card

Este es un paquete de pruebas de despliegue en NPM


### Sergio Alcántara Romero

## Ejemplo
````
import { ProductCard, ProductImage, ProductTitle, ProductButtons } from 'salcrom-product-card'
````

````
<ProductCard
    product={ product }
    initialValues={{
        count: 4,
        // maxCount: 10,
    }}
>
    {
        ({ reset, increaseBy, count, isMaxCountReached, maxCount }) => (
            <>
                <ProductImage />
                <ProductTitle />
                <ProductButtons />
            </>
        )
    }
</ProductCard>
````
