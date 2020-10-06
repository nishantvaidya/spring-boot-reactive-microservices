## Four prinicples of reactive microservice architecture.
     - Responsive : Responsive system provides timely responses against customer interaction.
      - Resilient : A system's ability to stay responsive under failure
            -- Replication - Running multiple instances behind load balancer.
            -- Containment and Isolation - Microservices, Message Driven
            -- Delegation -  Delegation tasks to other.
            -- Resilient - Circuit breaking.
      - Elastic - Elasticity is not scalability. Elasticity handles both increase and decrease load. Elasticity can be achieved using Sharding,
                 replication and workload distribution.
      - Message Driven.

## SAGA pattern for distributed microservices transaction.
   - Choreographed SAGA-  Centered on events going into global event store, publisher and consumer eg.Apache Kafka.
   - Orchestrated SAGA - Centered on commands rather than event, publisher

